---
title: Sign()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina il segno del valore intero con segno specificato.
type: docs
weight: 274
url: /it/system/mathf/sign/
---
## MathF::Sign(T) metodo

Determina il segno del valore intero con segno specificato.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo intero con segno |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore di cui determinare il segno |

### Valore di ritorno

- 1 se **value** è inferiore a 0; 0 se **value** è uguale a 0; 1 se **value** è superiore a 0

## MathF::Sign(T) metodo

Determina il segno del valore a virgola mobile specificato.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo a virgola mobile dell'argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore di cui determinare il segno |

### Valore di ritorno

- 1 se **value** è inferiore a 0; 0 se **value** è uguale a 0; 1 se **value** è superiore a 0

## Vedi anche

* Struttura [MathF](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)