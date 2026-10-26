---
title: Round()
second_title: Riferimento API di Aspose.Slides per C++
description: Arrotonda il valore specificato al valore intero più vicino.
type: docs
weight: 157
url: /it/system/math/round/
---
## Math::Round(double) metodo

Arrotonda il valore specificato al valore intero più vicino.

```cpp
static double System::Math::Round(double a)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **double** | Il valore da arrotondare |

### Valore restituito

**a** arrotondato al valore intero più vicino

## Math::Round(double, int) metodo

Arrotonda il valore specificato al valore più vicino con il numero di cifre frazionarie specificato.

```cpp
static double System::Math::Round(double value, int digits)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Math::Round(double, MidpointRounding) metodo

Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da arrotondare |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più vicini. |

### Valore restituito

**value** arrotondato al valore intero più vicino

## Math::Round(double, int, MidpointRounding) metodo

Arrotonda il valore specificato al valore più vicino con il numero di cifre frazionarie specificato. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più vicini. |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Math::Round(const Decimal\&) metodo

Arrotonda il valore specificato al valore intero più vicino.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Il valore da arrotondare |

### Valore restituito

**d** arrotondato al valore intero più vicino

## Math::Round(const Decimal\&, int) metodo

Arrotonda il valore specificato al valore più vicino con il numero di cifre frazionarie specificato.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Math::Round(const Decimal\&, MidpointRounding) metodo

Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Il valore da arrotondare |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più vicini. |

### Valore restituito

**d** arrotondato al valore intero più vicino

## Math::Round(const Decimal\&, int, MidpointRounding) metodo

Arrotonda il valore specificato al valore più vicino con il numero di cifre frazionarie specificato. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante da due numeri più vicini.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Il valore da arrotondare |
| digits | int | Il numero di cifre frazionarie nel valore arrotondato |
| mode | [MidpointRounding](../../midpointrounding/) | Specifica come eseguire l'arrotondamento se **value** è equidistante da due numeri più vicini. |

### Valore restituito

Il numero con il numero di cifre specificato più vicino a **value**

## Vedi anche

* Enum [MidpointRounding](../../midpointrounding/)
* Classe [Decimal](../../decimal/)
* Struct [Math](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)