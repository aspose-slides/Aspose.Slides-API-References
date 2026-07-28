---
title: Sign()
second_title: Aspose.Slides dla C++ — odniesienie API
description: Określa znak podanej liczby całkowitej ze znakiem.
type: docs
weight: 274
url: /pl/system/math/sign/
---
## Math::Sign(T) metoda


Określa znak podanej liczby całkowitej ze znakiem.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The integral signed type |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### Wartość zwracana

- 1 jeśli **value** jest mniejsze niż 0; 0 jeśli **value** jest równe 0; 1 jeśli **value** jest większe niż 0

## Math::Sign(T) metoda


Określa znak podanej liczby zmiennoprzecinkowej.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The floating point type of the argument |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### Wartość zwracana

- 1 jeśli **value** jest mniejsze niż 0; 0 jeśli **value** jest równe 0; 1 jeśli **value** jest większe niż 0

## Math::Sign(const Decimal\&) metoda


Określa znak podanej liczby dziesiętnej.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to determine the sign of |

### Wartość zwracana

- 1 jeśli **value** jest mniejsze niż 0; 0 jeśli **value** jest równe 0; 1 jeśli **value** jest większe niż 0

## Zobacz także

* Klasa [Decimal](../../decimal/)
* Struktura [Math](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)