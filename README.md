# Calculadora Simples de Lucro (por Itens) + Relatório em PDF

Uma aplicação web **simples e prática** (HTML + CSS + JavaScript) para calcular **lucro de compras e vendas**, permitindo adicionar vários itens com preços diferentes e gerar um **relatório em PDF**.

Ideal para quem trabalha com **revenda de produtos** e quer saber rapidamente:
- Quanto investiu
- Quanto vai vender
- Quanto vai lucrar (em R$ e %)

---

## ✨ Funcionalidades

- ✅ Adicionar itens com:
  - Nome (opcional)
  - Preço de compra
  - Preço de venda
  - Quantidade
- ✅ Lista dinâmica de itens
- ✅ Recalcula automaticamente os valores
- ✅ Remover item individual
- ✅ Limpar todos os itens
- ✅ Gerar **PDF** com:
  - Compra unitária
  - Venda unitária
  - Quantidade
  - Total de compra por item
  - Total de venda por item
  - Lucro por item
  - Resumo geral com totais e porcentagens

---

## 🧮 Como os cálculos funcionam

### Por item
- **Total de compra** = preço de compra × quantidade  
- **Total de venda** = preço de venda × quantidade  
- **Lucro** = total de venda − total de compra  

### Resumo geral
- **Lucro total (R$)** = total vendido − total investido  
- **Markup (%)** = (lucro ÷ total investido) × 100  
- **Margem (%)** = (lucro ÷ total vendido) × 100  

> O valor exibido como **Lucro (%)** é o *Markup*, pois é o percentual mais usado no dia a dia.

---

## 🚀 Como usar

### Opção 1: Abrir direto no navegador
1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador

Pronto. Não precisa instalar nada ✅

### Opção 2: Usar com Live Server (VS Code)
1. Instale a extensão **Live Server**
2. Clique com o botão direito em `index.html`
3. Selecione **Open with Live Server**

---

## 📄 Gerar relatório em PDF

1. Adicione os itens desejados
2. Clique em **Gerar PDF**
3. O relatório será baixado automaticamente

O PDF contém:
- Lista completa dos itens
- Totais por item
- Totais gerais
- Lucro em reais e porcentagem

---

## 🗂 Estrutura do projeto

```txt
/
├── index.html   # Aplicação completa (HTML + CSS + JS)
└── README.md
