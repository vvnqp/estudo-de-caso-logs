# 🔍 SAFE: Sentiment Analysis for Feedback Evaluation

**SAFE** é uma ferramenta interativa para análise de sentimentos em interações de chatbots e avaliações de produtos, com foco na detecção de respostas impróprias ou desalinhadas com o contexto. Utiliza técnicas de Processamento de Linguagem Natural (PLN), análise de confiabilidade e visualização gráfica para auxiliar na interpretação de feedbacks.

## 🧠 Funcionalidades Principais

- **Limpeza e pré-processamento** textual, incluindo remoção de stopwords e normalização.
- **Análise de sentimentos com VADER**, categorizando reviews como positivo, neutro ou negativo para análise de dados.
- **Detecção de incongruência** entre nota e sentimento (ex: nota alta com sentimento negativo).
- **Cálculo de confiabilidade** da análise com base em intensidade e consistência do score.
- **Identificação de temas relevantes sobre as vendas** por extração de palavras-chave críticas.
- **Visualizações gráficas** da distribuição de sentimentos, temas e confiabilidade.
- **Interface gráfica com Streamlit**, intuitiva e funcional, permitindo operação com poucos cliques.

## 🎯 Público-Alvo

- **Gerentes de Produto** — Avaliam pontos fortes e fracos com base em feedbacks reais.
- **Equipes de Marketing** — Identificam temas positivos para uso estratégico em campanhas.
- **Suporte ao Cliente** — Detectam problemas recorrentes e gargalos na experiência do usuário.
- **Desenvolvedores** — Priorizam correções com base no impacto emocional do feedback.

## 🛠️ Principais Tecnologias Utilizadas

- **Python 3**
- **Streamlit** — Interface gráfica
- **NLTK + VADER** — Processamento de linguagem e análise de sentimento
- **Matplotlib / Seaborn** — Visualizações gráficas

## Instalação e Configuração

1. Clone o repositório:

   ```bash
   git clone https://github.com/vvnqp/estudo-de-caso-logs.git
   cd estudo-de-caso-logs
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o programa:

   ```bash
   cd .\src\
   python -m streamlit run .\main.py
   ```

> ## **Importante:** 
> - A biblioteca `nltk` pode precisar de instalação adicional dependendo do seu sistema operacional.
> - É necessário dar cd na pasta .\src\ do projeto antes de executar o streamlit para evitar conflitos.

## Organização do Projeto

```
estudo-de-caso-logs/
│
├── src/
│ ├── main.py # Executável principal com interface Streamlit
│ ├── preprocessor.py # Limpeza e normalização de texto
│ ├── sentiment_analyzer.py # Análise de sentimentos com VADER
│ ├── keyword_detector.py # Identificação de palavras-chave para o dicionário.
│ ├── visualization.py # Geração de gráficos com matplotlib/seaborn
│ ├── data_loader.py # Carregamento e manipulação de dados
│ └── data/
│ └── amazon_reviews.csv # Base de dados de avaliações da Amazon
│
├── requirements.txt # Dependências do projeto
├── README.md # Este arquivo
└── .gitignore # Arquivos ignorados pelo Git
```

## 👥 Equipe

| Nome | GitHub |
|------|--------|
| Vinícius Moreno | [@vnqp](https://github.com/vnqp) |
| Gustavo Luz | [@guluz20](https://github.com/guluz20) |

---

## 🧠 Disciplinas Envolvidas

- Linguagens Formais e Autômatos

---

## 🏫 Informações Acadêmicas

- Universidade: **Universidade Braz Cubas**
- Curso: **Ciência da Computação**
- Semestre: 6º
- Período: Manhã
- Professora orientadora: **Dra. Andréa Ono Sakai**
- Evento: **Mostra de Tecnologia 1º Semestre de 2025**
- Local: Laboratório 12
- Datas: 05 e 06 de junho de 2025

---

## 📄 Licença

MIT License — sinta-se à vontade para utilizar, estudar e adaptar este projeto.

