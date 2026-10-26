---
title: Array()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom array.
type: docs
weight: 1
url: /sv/system/array/array/
---
## Array::Array() konstruktor

Skapar en tom array.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) konstruktor

Fyllningskonstruktor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Initial storlek på arrayen |
| init | const T\& | Det initiala värdet som används för att fylla arrayen med |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) konstruktor

Fyllningskonstruktor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ValueType | Typ av initialt värde |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Initial storlek på arrayen |
| init | [ValueType](../valuetype/) | Det initiala värdet som används för att fylla arrayen med |

## Array::Array(int, const T) konstruktor

Fyllningskonstruktor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Initial storlek på arrayen |
| inits | const T | Värden att fylla arrayen med |

## Array::Array(vector_t\&&) konstruktor

Flyttkonstruktor.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, vars element tas emot av arrayen |

## Array::Array(const vector_t\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector att kopiera värden från |

## Array::Array(const std::vector\<Q\>\&) konstruktor

Skapar ett [Array](../)-objekt och fyller det med värden kopierade från ett std::vector-objekt vars värdetyp är densamma som **T** men skiljer sig från **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typen av elementen i std::vector-objektet att kopiera elementen från |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector att kopiera värdena från |

## Array::Array(std::vector\<Q\>\&&) konstruktor

Skapar ett [Array](../)-objekt och fyller det med värden flyttade från ett std::vector-objekt vars värdetyp är densamma som **T** men skiljer sig från **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typen av elementen i std::vector-objektet att flytta elementen från |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector att kopiera värdena från |

## Array::Array(std::initializer_list\<UnderlyingType\>) konstruktor

Skapar ett [Array](../)-objekt och fyller det med värden från den angivna initialiseringslistan som innehåller element av typen **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Initialiseringslista som innehåller element att fylla arrayen med |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) konstruktor

Skapar ett [Array](../)-objekt och fyller det med värden från den angivna arrayen som innehåller element av typen **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| InitArraySize | Antal element i **init**-arrayen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) att kopiera till den array som konstrueras. |

## Array::Array(std::initializer_list\<bool\>, int) konstruktor

Skapar ett [Array](../)-objekt och fyller det med värden från den angivna initialiseringslistan som innehåller element av bool-typ.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Initialiseringslista som innehåller element att fylla arrayen med |

## Se även

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)