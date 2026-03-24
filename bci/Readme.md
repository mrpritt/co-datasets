# BCI - Formato de Instância

Este diretório contém materiais do problema **Baile Celeste Imperial (BCI)**.

## Formato de Entrada

Primeira linha:

```text
n m K beta
```

- `n`: número de nobres (usuários).
- `m`: número de encaixes (âncoras/sensores).
- `K`: cota mínima de ganho coberto.
- `beta`: expoente de custo da auréola (inteiro, `beta >= 1`).

Próximas `n` linhas (uma por nobre):

```text
x_i g_i pi_i
```

- `x_i`: coordenada do nobre na linha.
- `g_i`: ganho do nobre (profit).
- `pi_i`: penalidade se o nobre ficar descoberto.

Próximas `m` linhas (uma por encaixe):

```text
a_j
```

- `a_j`: coordenada do encaixe na linha.
