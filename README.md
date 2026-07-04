# 🏫 Portal INCLUISABER - Rede Municipal de Ensino

O **INCLUISABER** é uma plataforma digital open-source voltada para o apoio pedagógico municipal e inclusão escolar. O sistema oferece trilhas progressivas de exercícios focadas em **Alfabetização (Consciência Fonológica)**, **Ensino Fundamental** e **Módulos Clínicos Adaptados para TEA (Transtorno do Espectro Autista)**.

A plataforma conta com uma **Área do Professor** integrada, permitindo o cadastro de novas atividades personalizadas diretamente pela interface e um **Painel do Profissional** para monitoramento de desempenho e mapeamento de lacunas de aprendizado em tempo real.

> 🚀 **Hospedagem Simplificada:** Esta versão foi projetada para rodar de forma 100% estática (Serverless). Pode ser hospedada gratuitamente no **GitHub Pages** sem a necessidade de configurar servidores ou bancos de dados complexos, utilizando o `localStorage` do navegador.

---

## ✨ Funcionalidades Principais

* **Módulo de Alfabetização:** Atividades estruturadas com lacunas (Ex: `B _ L A`) para identificação de fonemas e vogais/consoantes.
* **Módulo Clínico TEA (Modo Clean):** Interface minimalista com alto contraste, fontes simplificadas, sem poluição visual e com cards de resposta gigantes focados em pareamento visual e rotinas.
* **Acessibilidade com Áudio:** Função de síntese de voz integrada (**🔊 Ouvir Comando**) para leitura dos enunciados de forma nativa e inclusiva.
* **Área de Gestão do Professor:** Painel administrativo oculto para cadastrar novas questões de forma intuitiva.
* **Mapeamento de Erros:** Gráfico lógico em tempo real que exibe os desvios pedagógicos e as letras mais erradas pelo aluno durante a sessão.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** - Estrutura semântica da aplicação.
* **Tailwind CSS** - Estilização moderna, responsiva e suporte ao *Modo Clean*.
* **JavaScript (Vanilla)** - Lógica de estados, persistência com `Web Storage API` e motor de acessibilidade `SpeechSynthesis`.

---

## 🚀 Como Rodar o Projeto Localmente

Não há dependências ou processos de build complicados!

1. Baixe os arquivos ou clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/incluisaber.git](https://github.com/seu-usuario/incluisaber.git)
