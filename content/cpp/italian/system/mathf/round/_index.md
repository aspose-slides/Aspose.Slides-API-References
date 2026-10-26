---
title: Round()
second_title: Riferimento API di Aspose.Slides per C++
description: Arrotonda il valore specificato al valore intero più vicino.
type: docs
weight: 157
url: /it/system/mathf/round/
---
## MathF::Round(float) metodo

Arrotonda il valore specificato al valore intero più vicino.

```cpp
static float System::MathF::Round(float a)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **float** | Il valore da arrotondare |

### Valore restituito

**a** arrotondato al valore intero più vicino

## MathF::Round(float, int) metodo

Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## MathF::Round(float, MidpointRounding) metodo

Arrotonda il valore specificato al valore intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più prossimi.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da arrotondare |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più prossimi. |

### Valore restituito

**value** arrotondato al valore intero più vicino

## MathF::Round(float, int, MidpointRounding) metodo

Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più prossimi.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più prossimi. |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Vedi anche

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)