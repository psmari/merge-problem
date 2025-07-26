# Desafio Git: Resolva o Conflito de Merge no Projeto Python

Bem-vindo(a) ao desafio prático de Git! 🎉

---

## Contexto

Este repositório contém um arquivo Python chamado `calculadora.py` que está com um **conflito de merge não resolvido** com a branch feat/soma que temos que mergear na main. Seu objetivo é entender o conflito, resolver corretamente e finalizar o merge.

---

## O que é um conflito de merge?

Quando duas branches alteram o mesmo trecho de código de forma diferente, o Git não consegue decidir automaticamente qual versão manter. Ele marca esse trecho com símbolos especiais:

```python
<<<<<<< HEAD
# código da branch atual (ex: main)
=======
# código da branch que está sendo mesclada (ex: melhoria-saudacao)
>>>>>>> melhoria-saudacao
