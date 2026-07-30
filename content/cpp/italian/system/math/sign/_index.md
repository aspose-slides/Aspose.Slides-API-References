---
title: Sign()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina il segno del valore intero con segno specificato.
type: docs
weight: 274
url: /it/system/math/sign/
---
## Math::Sign(T) metodo


Determina il segno del valore intero con segno specificato.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
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

- 1 se **value** è minore di 0; 0 se **value** è uguale a 0; 1 se **value** è maggiore di 0

## Math::Sign(T) metodo


Determina il segno del valore in virgola mobile specificato.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo a virgola mobile dell’argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore di cui determinare il segno |

### Valore di ritorno

- 1 se **value** è minore di 0; 0 se **value** è uguale a 0; 1 se **value** è maggiore di 0

## Math::Sign(const Decimal\&) metodo


Determina il segno del valore decimale specificato.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Il valore di cui determinare il segno |

### Valore di ritorno

- 1 se **value** è minore di 0; 0 se **value** è uguale a 0; 1 se **value** è maggiore di 0

## Vedi anche

* Classe [Decimal](../../decimal/)
* Struttura [Math](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)