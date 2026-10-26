---
title: Array()
second_title: Aspose.Slides for C++ API-referentie
description: Construeert een lege array.
type: docs
weight: 1
url: /nl/system/array/array/
---
## Array::Array() constructor

Construeert een lege array.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) constructor

Vullende constructor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| count | int | Initiële grootte van de array |
| init | const T\& | De initiële waarde die wordt gebruikt om de array mee te vullen |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor

Vullende constructor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ValueType | Type van de initiële waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Initiële grootte van de array |
| init | [ValueType](../valuetype/) | De initiële waarde die wordt gebruikt om de array mee te vullen |

## Array::Array(int, const T) constructor

Vullende constructor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| count | int | Initiële grootte van de array |
| inits | const T | Waarden om de array mee te vullen |

## Array::Array(vector_t\&&) constructor

Verplaatsende constructor.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, waarvan de elementen door de array worden overgenomen |

## Array::Array(const vector_t\&) constructor

Kopieerconstructor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector om waarden van te kopiëren |

## Array::Array(const std::vector\<Q\>\&) constructor

Construeert een [Array](../) object en vult het met waarden gekopieerd uit een std::vector-object waarvan het type van de waarden hetzelfde is als **T**, maar verschilt van **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Het type van de elementen van het std::vector-object waarvan de elementen moeten worden gekopieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector om de waarden van te kopiëren |

## Array::Array(std::vector\<Q\>\&&) constructor

Construeert een [Array](../) object en vult het met waarden die zijn verplaatst uit een std::vector-object waarvan het type van de waarden hetzelfde is als **T**, maar verschilt van **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Het type van de elementen van het std::vector-object waarvan de elementen moeten worden verplaatst |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector om de waarden van te verplaatsen |

## Array::Array(std::initializer_list\<UnderlyingType\>) constructor

Construeert een [Array](../) object en vult het met waarden uit de opgegeven initializer-list die elementen van het type **UnderlyingType** bevat.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Initializer-list met elementen om de array mee te vullen |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor

Construeert een [Array](../) object en vult het met waarden uit de opgegeven array die elementen van het type **UnderlyingType** bevat.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| InitArraySize | Aantal elementen van de **init**-array. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) om te kopiëren in de array die wordt geconstrueerd. |

## Array::Array(std::initializer_list\<bool\>, int) constructor

Construeert een [Array](../) object en vult het met waarden uit de opgegeven initializer-list die elementen van het type bool bevat.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Initializer-list met elementen om de array mee te vullen |

## Zie ook

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)