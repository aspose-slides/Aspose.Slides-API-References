---
title: IndexOf()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa indeks pierwszego wystąpienia określonego elementu w tablicy.
type: docs
weight: 131
url: /pl/system/array/indexof/
---
## Array::IndexOf(const T\&) const metoda


Określa indeks pierwszego wystąpienia określonego elementu w tablicy.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Element, którego indeks ma zostać określony |

### Wartość zwracana

[Index](../../index/) indeks pierwszego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metoda


Określa indeks pierwszego wystąpienia określonego elementu w tablicy.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Element, którego indeks ma zostać określony |

### Wartość zwracana

[Index](../../index/) indeks pierwszego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metoda


Określa indeks pierwszego wystąpienia określonego elementu w tablicy, rozpoczynając od określonego indeksu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Element, którego indeks ma zostać określony |
| startIndex | int | [Index](../../index/) indeks, od którego rozpoczyna się wyszukiwanie |

### Wartość zwracana

[Index](../../index/) indeks pierwszego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metoda


Określa indeks pierwszego wystąpienia określonego elementu w zakresie elementów tablicy określonym przez indeks początkowy i liczbę elementów w zakresie.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Element, którego indeks ma zostać określony |
| startIndex | int | [Index](../../index/) indeks, od którego rozpoczyna się wyszukiwanie |
| count | int | Number of elements of the range to search in |

### Wartość zwracana

[Index](../../index/) indeks pierwszego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)