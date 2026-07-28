---
title: Array()
second_title: Aspose.Slides C++ API-referencia
description: Üres tömböt hoz létre.
type: docs
weight: 1
url: /hu/system/array/array/
---
## Array::Array() konstruktor


Egy üres tömböt hoz létre.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) konstruktor


Kitöltő konstruktor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| count | int | A tömb kezdeti mérete |
| init | const T\& | A tömb kitöltéséhez használt kezdeti érték |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) konstruktor


Kitöltő konstruktor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ValueType | Kezdeti érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | A tömb kezdeti mérete |
| init | [ValueType](../valuetype/) | A tömb kitöltéséhez használt kezdeti érték |

## Array::Array(int, const T) konstruktor


Kitöltő konstruktor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| count | int | A tömb kezdeti mérete |
| inits | const T | A tömb kitöltéséhez használt értékek |

## Array::Array(vector_t\&&) konstruktor


Mozgató konstruktor.

```cpp
System::Array<T>::Array(vector_t &&value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, elemei a tömb által felvett elemek |

## Array::Array(const vector_t\&) konstruktor


Másoló konstruktor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector, amelyből az értékek másolódnak |

## Array::Array(const std::vector\<Q\>\&) konstruktor


Létrehoz egy [Array](../) objektumot, és az értékeket egy std::vector objektumból másolja, amelynek értéktípusa ugyanaz, mint **T**, de eltér **UnderlyingType**-től.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | A std::vector objektum elemeinek típusa, amelyből a másolandó elemek származnak |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, amelyből az értékek másolódnak |

## Array::Array(std::vector\<Q\>\&&) konstruktor


Létrehoz egy [Array](../) objektumot, és az értékeket egy std::vector objektumból mozgatja, amelynek értéktípusa ugyanaz, mint **T**, de eltér **UnderlyingType**-től.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | A std::vector objektum elemeinek típusa, amelyből a mozgatandó elemek származnak |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, amelyből az értékek másolódnak |

## Array::Array(std::initializer_list\<UnderlyingType\>) konstruktor


Létrehoz egy [Array](../) objektumot, és a megadott initializer list-ből tölt fel értékekkel, amely **UnderlyingType** típusú elemeket tartalmaz.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Initializer list, amely az elemeket tartalmazza a tömb kitöltéséhez |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) konstruktor


Létrehoz egy [Array](../) objektumot, és a megadott tömbből tölti fel értékekkel, amely **UnderlyingType** típusú elemeket tartalmaz.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| InitArraySize | A **init** tömb elemeinek száma. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) a létrehozott tömbbe másolva. |

## Array::Array(std::initializer_list\<bool\>, int) konstruktor


Létrehoz egy [Array](../) objektumot, és a megadott initializer list-ből tölt fel értékekkel, amely bool típusú elemeket tartalmaz.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Initializer list, amely az elemeket tartalmazza a tömb kitöltéséhez |

## Lásd még

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)