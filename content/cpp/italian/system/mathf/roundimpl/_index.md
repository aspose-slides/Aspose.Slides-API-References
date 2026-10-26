---
title: RoundImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre decimali. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.
type: docs
weight: 287
url: /it/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) metodo

Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre decimali. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da arrotondare |
| digits | int | Il numero di cifre decimali nel valore arrotondato |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante dai due numeri più vicini. |

### Valore restituito

Il numero con il numero specificato di cifre più vicino a **value**

## Vedi anche

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)