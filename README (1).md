# 📊 Dashboard de Vendas — Excel

**Stack:** Microsoft Excel (Tabelas Dinâmicas, Gráficos Dinâmicos, Slicers)
**Tema:** Análise de vendas de produtos eletrônicos por lojista, canal, período e estado
**Objetivo:** Consolidar 2.109 registros de vendas (2022-2023) em um dashboard interativo que permite filtrar e comparar o desempenho por múltiplas dimensões

---

## 📖 O Contexto

Esta planilha simula o dashboard de vendas de um distribuidor de eletrônicos (desktops, notebooks, monitores, TVs e periféricos), com dados de 5 redes varejistas em 27 estados do Brasil — cobrindo o período de 2022 até agosto de 2023, totalizando **R$ 51.655.622** em receita bruta.

---

## 🗂️ Estrutura da Planilha

| Aba | Conteúdo |
|---|---|
| `ExtraçãoDados` | Base com 2.109 registros (lojista, canal, data, região, produto, receita e margem) |
| `Planilha1` | Tabela dinâmica: receita total por lojista |
| `Planilha2` | Tabela dinâmica: receita por canal (E-Commerce vs Loja Física) |
| `Planilha3` | Tabela dinâmica: receita por período (mês/ano) |
| `Planilha4` | Tabela dinâmica: receita por estado |
| `Dashboard` | Painel centralizado com 7 gráficos dinâmicos e slicers interativos |

---

## ⚙️ Recursos Utilizados

- **4 Tabelas Dinâmicas** alimentando os gráficos do dashboard
- **7 Gráficos Dinâmicos** (barras, linhas, mapas e treemap)
- **Slicers** para filtro interativo por lojista, canal e período
- Dados organizados em formato tabular estruturado na aba base

---

## 📊 Principais Números

### 🏆 Receita por Lojista

| Lojista | Receita Total |
|---|---|
| Americanas | R$ 22.028.732 |
| Carrefour | R$ 12.942.258 |
| Kalunga | R$ 6.504.532 |
| Fast Shop | R$ 6.199.402 |
| Magazine Luiza | R$ 3.980.698 |
| **Total** | **R$ 51.655.622** |

**Insight:** Americanas concentra **42,6%** de toda a receita — mais que os outros 4 lojistas juntos se desconsiderarmos Carrefour. Magazine Luiza tem a menor participação (~7,7%).

---

### 🛒 E-Commerce vs Loja Física

| Canal | Receita | Participação |
|---|---|---|
| E-Commerce | R$ 35.668.772 | 69,1% |
| Loja Física | R$ 15.986.850 | 30,9% |

**Insight:** O canal digital representa quase **7 em cada 10 reais** vendidos — padrão consistente com o perfil de eletrônicos de alto valor, onde o consumidor pesquisa e compra online.

---

### 📅 Sazonalidade (2022 vs 2023)

| Período | Receita |
|---|---|
| 2022 (ano completo) | R$ 27.510.962 |
| 2023 (jan-ago) | R$ 24.144.660 |

Agosto/2023 foi o mês de pico isolado: **R$ 4.511.066** — quase o dobro da média mensal dos demais meses do ano.

---

### 🗺️ Top 5 Estados por Receita

| Estado | Receita |
|---|---|
| São Paulo | R$ 8.027.026 |
| Rio de Janeiro | R$ 5.889.550 |
| Santa Catarina | R$ 4.314.732 |
| Mato Grosso | R$ 3.039.164 |
| Ceará | R$ 2.502.244 |

**Insight:** SP + RJ concentram **27,1%** da receita nacional. Mato Grosso aparece em 4º lugar surpreendendo frente a estados maiores como Minas Gerais (R$ 1,9M) e Paraná (R$ 2,3M).

---

### 💰 Margem por Produto

| Produto | Margem |
|---|---|
| Monitor 27 pol | 50% |
| TV Ultra | 40% |
| Monitor 24 pol | 40% |
| Desktop Ultra | 35% |
| TV LED HD | 35% |
| Desktop Pro / Notebook 20 | 30% |
| Desktop Basic / Notebook 17 | 25% |
| Notebook 15 | 20% |
| Teclado | 15% |

**Insight:** Monitores têm a maior margem da linha (50%), enquanto periféricos como Teclado ficam em apenas 15% — produtos de alto volume, baixo valor e baixa rentabilidade.

---

## 🧠 Sobre as Habilidades Aplicadas

Nível: **intermediário em Excel** — construção e interpretação de tabelas dinâmicas, uso de PROCV e PROCH para relacionar dados entre abas, e análise de indicadores para extrair insights de negócio. Neste projeto especificamente, aplicado por meio de 4 tabelas dinâmicas, 7 gráficos dinâmicos interativos e slicers conectados ao dashboard.

---

## 🎥 Demonstração

![Dashboard em funcionamento](dashboard.gif)

---

## 📁 Estrutura do Projeto

```
Dashboard-Vendas-Excel/
├── Dashboard_vendas.xlsx   # Planilha completa (6 abas)
├── dashboard.gif           # Demonstração interativa do dashboard
└── README.md               # Este arquivo
```

---

## 🚀 Como Usar

1. Baixe o arquivo `Dashboard_vendas.xlsx`
2. Abra no Microsoft Excel
3. Use os **slicers** na aba Dashboard para filtrar por lojista, canal ou período — todos os gráficos atualizam automaticamente

---

📫 **Contato:** [LinkedIn](https://www.linkedin.com/in/simaosantana-a744372a7) · simaojoaosantana@gmail.com
