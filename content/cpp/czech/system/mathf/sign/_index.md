---
title: Sign()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje znaménko zadané podepsané celočíselné hodnoty.
type: docs
weight: 274
url: /cs/system/mathf/sign/
---
## MathF::Sign(T) metoda

Určuje znaménko zadané podepsané celočíselné hodnoty.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ podepsané celočíselné |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota, jejíž znaménko se má určit |

### Návratová hodnota

- 1 pokud **value** je menší než 0; 0 pokud **value** je rovno 0; 1 pokud **value** je větší než 0

## MathF::Sign(T) metoda

Určuje znaménko zadané hodnoty s plovoucí desetinnou čárkou.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ čísel s plovoucí desetinnou čárkou argumentu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota, jejíž znaménko se má určit |

### Návratová hodnota

- 1 pokud **value** je menší než 0; 0 pokud **value** je rovno 0; 1 pokud **value** je větší než 0

## Viz také

* Struktura [MathF](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)