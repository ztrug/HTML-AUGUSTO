# Layouts com CSS Flexbox e CSS Grid + Flexbox

Este repositório contém dois projetos demonstrando a construção de um layout utilizando:

- 🔹 Apenas **CSS Flexbox**
- 🔹 Combinação de **CSS Grid com Flexbox**

---

## 📁 Projetos

### 1. `flexbox-layout/`

Este projeto implementa um layout completo utilizando **apenas Flexbox** para estruturar os elementos da página. A organização do conteúdo foi feita com `display: flex`, utilizando `flex-direction`, `gap`, e `flex` para controle de proporções.

### 2. `grid-flexbox-layout/`
git add README.md
Este projeto utiliza **CSS Grid** para a estrutura geral da página e **Flexbox** para alinhar e organizar elementos internos. A divisão principal da página (como a separação entre o conteúdo e o `aside`) é feita com Grid, enquanto agrupamentos menores (como listas de artigos ou seções dentro do aside) usam Flexbox.

---

## 🔍 Diferenças Percebidas

| Aspecto                       | Apenas Flexbox                         | CSS Grid + Flexbox                         |
|------------------------------|----------------------------------------|--------------------------------------------|
| **Controle da estrutura geral** | Limitado ao fluxo linear (1D)          | Excelente controle em 2D (linhas e colunas)|
| **Alinhamento de áreas principais** | Requer mais aninhamento de elementos   | Pode ser feito diretamente com Grid        |
| **Flexibilidade interna**     | Ótimo para listas ou blocos alinhados | Continua sendo útil dentro de áreas        |
| **Código mais limpo**         | Pode precisar de mais `div`            | Menos marcação e maior controle visual     |
| **Curva de aprendizado**      | Mais simples                           | Requer mais entendimento das propriedades  |

---

## 🚀 Como visualizar

Basta abrir os arquivos `index.html` de cada pasta (`flexbox-layout/` e `grid-flexbox-layout/`) em um navegador para visualizar os layouts implementados.

---

## 📄 Licença

Este projeto está sob a licença MIT.
