# 🌐 Hello World - Landing Page

Um projeto prático de desenvolvimento web focado no desafio de construir uma **Hero Section** responsiva diretamente no código (HTML/CSS), testando a percepção visual, alinhamento e fluidez com um suporte prévio de design Figma.

O projeto conta com uma estrutura de cabeçalho com navegação, uma seção principal (*Hero*) com textos em hierarquia, botões de ação e adaptação completa para dispositivos móveis.

---

## 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando boas práticas do ecossistema front-end nativo:

* **HTML5 Semântico:** Estruturação da página dividida claramente entre áreas de navegação (`header`, `navbar`) e conteúdo principal (`hero`).
* **CSS3 Moderno:**
  * **Flexbox Layout:** Utilizado estrategicamente para criar distribuições de espaço dinâmicas (`justify-content: space-between`) e alinhamentos verticais em formato de coluna.
  * **CSS Nesting (Aninhamento):** Uso da nova sintaxe nativa para organizar estilos de forma hierárquica e limpa.
  * **Pseudo-classes (`:first-child`, `:last-child`):** Gerenciamento preciso de pesos (`font-weight`) e tamanhos de fontes sem a necessidade de criar classes repetitivas no HTML.
  * **Design Responsivo:** Implementação de `@media (max-width: 850px)` para reestruturar o layout em telas menores.

---

## 📱 Responsividade e Adaptação

O grande destaque técnico deste projeto está na transição de layout via Media Query para telas de até `850px`:
1. **Menu Hamburguer Oculto:** A barra de links (`.navbar`) é ocultada e uma imagem de menu (`img`) é ativada dinamicamente para preservar o espaço em telas mobile.
2. **Mudança de Fluxo (Grid/Pilha):** A seção `.hero` muda de uma disposição horizontal (lado a lado) para uma disposição vertical (`flex-direction: column`), garantindo que o texto e a imagem se ajustem perfeitamente à largura do dispositivo.
3. **Imagens Fluidas:** A imagem principal passa a ocupar `width: 100%`, evitando quebras de layout ou barras de rolagem horizontais indesejadas.

---

## 📸 Demonstração

> 🔗 **Acesse o projeto online aqui:** https://yurikoga.github.io/Projeto_Planeta/
