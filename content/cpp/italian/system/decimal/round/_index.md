---
title: Round()
second_title: Riferimento API di Aspose.Slides per C++
description: Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini.
type: docs
weight: 404
url: /it/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metodo

Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../)\& | Il valore da arrotondare |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante dai due numeri più vicini. |

### Valore restituito

**d** arrotondato al valore intero più vicino

## Decimal::Round(const Decimal\&, int, MidpointRounding) metodo

Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../)\& | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante dai due numeri più vicini. |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Vedi anche

* Enum [MidpointRounding](../../midpointrounding/)
* Classe [Decimal](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)