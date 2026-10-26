---
title: Array()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy pustą tablicę.
type: docs
weight: 1
url: /pl/system/array/array/
---
## Array::Array() konstruktor

Tworzy pustą tablicę.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) konstruktor

Konstruktor wypełniający.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| count | int | Początkowy rozmiar tablicy |
| init | const T\& | Początkowa wartość używana do wypełnienia tablicy |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) konstruktor

Konstruktor wypełniający.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ValueType | Typ początkowej wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Początkowy rozmiar tablicy |
| init | [ValueType](../valuetype/) | Początkowa wartość używana do wypełnienia tablicy |

## Array::Array(int, const T) konstruktor

Konstruktor wypełniający.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| count | int | Początkowy rozmiar tablicy |
| inits | const T | Wartości używane do wypełnienia tablicy |

## Array::Array(vector_t\&&) konstruktor

Konstruktor przenoszący.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, elementy którego są przejmowane przez tablicę |

## Array::Array(const vector_t\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector, z którego kopiowane są wartości |

## Array::Array(const std::vector\<Q\>\&) konstruktor

Tworzy obiekt [Array](../) i wypełnia go wartościami skopiowanymi z obiektu std::vector, którego typ wartości jest taki sam jak **T**, ale różny od **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ elementów obiektu std::vector, z którego kopiowane są elementy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, z którego kopiowane są wartości |

## Array::Array(std::vector\<Q\>\&&) konstruktor

Tworzy obiekt [Array](../) i wypełnia go wartościami przeniesionymi z obiektu std::vector, którego typ wartości jest taki sam jak **T**, ale różny od **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ elementów obiektu std::vector, z którego przenoszone są elementy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, z którego kopiowane są wartości |

## Array::Array(std::initializer_list\<UnderlyingType\>) konstruktor

Tworzy obiekt [Array](../) i wypełnia go wartościami z określonej listy inicjalizacyjnej zawierającej elementy typu **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Lista inicjalizacyjna zawierająca elementy używane do wypełnienia tablicy |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) konstruktor

Tworzy obiekt [Array](../) i wypełnia go wartościami z określonej tablicy zawierającej elementy typu **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| InitArraySize | Liczba elementów tablicy **init**. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) do skopiowania do tworzanej tablicy. |

## Array::Array(std::initializer_list\<bool\>, int) konstruktor

Tworzy obiekt [Array](../) i wypełnia go wartościami z określonej listy inicjalizacyjnej zawierającej elementy typu bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Lista inicjalizacyjna zawierająca elementy używane do wypełnienia tablicy |

## Zobacz także

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)