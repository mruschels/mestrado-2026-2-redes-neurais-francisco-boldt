# Redes Neurais Artificiais (2026/2)

Repositório com as entregas das tarefas práticas da disciplina **Redes Neurais
Artificiais** do Mestrado Profissional em Computação Aplicada (PPComp) — Ifes,
Campus Serra.

- **Semestre:** 2026/2
- **Professor:** Prof. Francisco Boldt
- **Aluno:** Moisés Ruschel Schorr

## Estrutura do repositório

```text
.
├── github-aulas-prof-boldt/  # Notebooks e programa (Prof. Francisco Boldt)
├── tarefa1/                  # MLP com Backpropagation vs. Scikit-Learn
├── tarefa2/                  # CNN no MNIST original (arquivos IDX)
├── tarefa3/                  # Forecasting de séries temporais (vs. Naïve)
└── tarefa4/                  # Sentimento no dataset IMDB (Transformers)
```

## Tarefas

| Pasta | Tema | Objetivo resumido |
| :-- | :-- | :-- |
| [`tarefa1/`](tarefa1/) | MLP e Backpropagation | Implementar um MLP configurável (camadas, neurônios e ativações por camada) e comparar com o `MLPClassifier` do Scikit-Learn. |
| [`tarefa2/`](tarefa2/) | CNN no MNIST original | Baixar, ler e pré-processar a base original do MNIST (arquivos IDX, fora do Keras) e treiná-la com rede convolucional. |
| [`tarefa3/`](tarefa3/) | *Forecasting* | Aplicar técnicas de previsão de séries temporais vistas em aula em outra base de dados, comparando com *baseline* ingênuo (*Naïve*). |
| [`tarefa4/`](tarefa4/) | NLP / Sentimento (IMDB) | Utilizar `transformers.pipeline` (Hugging Face) para análise de sentimento na base IMDB (`aclImdb_v1`). |

## Material das aulas

A pasta [`github-aulas-prof-boldt/`](github-aulas-prof-boldt/) reúne o programa
da disciplina e os notebooks de referência disponibilizados pelo Prof. Francisco
Boldt em seu repositório público
([`fboldt/aulasann`](https://github.com/fboldt/aulasann)).

## Ambiente sugerido

Os notebooks são executados em ambiente virtual Python (3.13+), utilizando
bibliotecas padrão de aprendizado de máquina e *deep learning* (`numpy`,
`scikit-learn`, `matplotlib`, `jupyter`, `torch` e `transformers`, conforme a
tarefa). Bases de dados baixadas localmente ficam na pasta `data/` (ignorada
pelo Git).
