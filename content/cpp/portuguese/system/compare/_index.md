---
title: Compare()
second_title: Referência da API Aspose.Slides para C++
description: Compara dois valores.
type: docs
weight: 2731
url: /pt/system/compare/
---
## System::Compare(const TA\&, const TB\&) função

Compara dois valores.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TA | O tipo do primeiro comparando |
| TB | O tipo do segundo comparando |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const TA\& | O primeiro comparando |
| b | const TB\& | O segundo comparando |

### Valor de retorno

- 1 se **a** for menor que **b**; 0 se os valores forem iguais; 1 se **a** for maior que **b**

## System::Compare(const TA\&, const TB\&) função

Compara dois valores de ponto flutuante.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TA | O tipo do primeiro comparando |
| TB | O tipo do segundo comparando |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const TA\& | O primeiro comparando |
| b | const TB\& | O segundo comparando |

### Valor de retorno

- 1 se **a** for menor que **b**; 0 se os valores forem iguais; 1 se **a** for maior que **b**

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)