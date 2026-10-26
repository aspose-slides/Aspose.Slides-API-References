---
title: Sign()
second_title: Odwołanie API Aspose.Slides dla C++
description: Określa znak podanej liczby całkowitej ze znakiem.
type: docs
weight: 274
url: /pl/system/mathf/sign/
---
## MathF::Sign(T) metoda


Określa znak podanej liczby całkowitej ze znakiem.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ całkowity ze znakiem |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Wartość, której znak ma zostać określony |

### Wartość zwracana

- 1 jeśli **value** jest mniejsze od 0; 0 jeśli **value** jest równe 0; 1 jeśli **value** jest większe od 0

## MathF::Sign(T) metoda


Określa znak podanej wartości zmiennoprzecinkowej.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ zmiennoprzecinkowy argumentu |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Wartość, której znak ma zostać określony |

### Wartość zwracana

- 1 jeśli **value** jest mniejsze od 0; 0 jeśli **value** jest równe 0; 1 jeśli **value** jest większe od 0

## Zobacz także

* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)