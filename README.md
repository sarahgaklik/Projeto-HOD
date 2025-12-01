# 🐉 House of the Dragon - Carrossel de Personagens

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</div>

<br />

<p align="center">
  <img src="https://via.placeholder.com/800x400.png?text=Preview+do+Projeto+House+of+the+Dragon" alt="Demonstração do Projeto" width="100%">
</p>

## 💻 Sobre o Projeto

Este é um projeto interativo desenvolvido para apresentar os dragões da série **House of the Dragon**. A aplicação consiste em um carrossel de imagens com transições suaves e alteração dinâmica de conteúdo (título e descrição) baseada na interação do usuário.

O objetivo principal foi praticar a manipulação do **DOM** (Document Object Model) com JavaScript e aprofundar conhecimentos em **CSS Flexbox** e **Design Responsivo**.

## ✨ Funcionalidades

- **Navegação Interativa:** Botões de controle que permitem alternar entre os dragões.
- **Troca Dinâmica de Fundo:** A imagem de fundo muda suavemente com base na seleção (Balerion, Syrax, Vhagar, etc.).
- **Conteúdo Contextual:** O título e a descrição são atualizados automaticamente conforme o dragão selecionado.
- **Animações CSS:** Transições de opacidade (`fade-in`) para uma experiência visual agradável.
- **Design Responsivo:** Layout adaptável para Desktops, Tablets e Smartphones (Breakpoints ajustados para 1280px, 768px e 425px).

## 🛠 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica.
- **CSS3:** Estilização, Flexbox, Media Queries e Keyframes.
- **JavaScript (ES6):** Lógica de interação, `querySelectorAll`, `forEach` e manipulação de classes.

## 📂 Estrutura de Arquivos

O projeto segue a seguinte organização:
├── index.html # Estrutura principal 
├── src/ │ 
  ├── css/ │
    ├── estilos.css # Estilos gerais │
    ├── reset.css # Reset CSS │ 
    │ └── responsivo.css # Adaptações mobile │ 
  ├── js/ │ 
    │ └── index.js # Lógica do carrossel │ 
  ├── imagens/ # Imagens dos dragões 
    │ └── fontes/ # Fonte personalizada (GOT)

## 🧠 Lógica do Código

O desenvolvimento do JavaScript foi pautado em passos lógicos claros para garantir a funcionalidade:

1.  **Seleção de Elementos:** Recuperação dos botões, imagens e textos do DOM.
2.  **Escuta de Eventos:** Monitoramento do clique em cada botão do carrossel.
3.  **Gestão de Estado:**
    - Remoção da classe `selecionado` do botão anterior.
    - Adição da classe `selecionado` ao botão clicado.
    - Ocultação da imagem e texto ativos anteriormente.
    - Exibição da nova imagem e texto correspondentes ao índice do botão.
