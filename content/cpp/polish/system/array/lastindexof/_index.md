---
title: LastIndexOf()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa indeks ostatniego wystąpienia określonego elementu w zakresie elementów tablicy określonym przez indeks początkowy i liczbę elementów w zakresie.
type: docs
weight: 703
url: /pl/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metoda


Określa indeks ostatniego wystąpienia określonego elementu w zakresie elementów tablicy określonym przez indeks początkowy i liczbę elementów w zakresie.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ArrayType | Typ elementów w docelowej tablicy |
| ValueType | typ elementu, którego szukamy w tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Indeks elementu, którego pozycja ma zostać określona |
| startIndex | int | [Index](../../index/) od którego rozpoczyna się wyszukiwanie |
| count | int | Liczba elementów zakresu, w którym odbywa się wyszukiwanie |

### Wartość zwracana

[Index](../../index/) ostatniego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metoda


Określa indeks ostatniego wystąpienia określonego elementu w tablicy począwszy od podanego indeksu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ArrayType | Typ elementów w docelowej tablicy |
| ValueType | typ elementu, którego szukamy w tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Indeks elementu, którego pozycja ma zostać określona |
| startIndex | int | [Index](../../index/) od którego rozpoczyna się wyszukiwanie |

### Wartość zwracana

[Index](../../index/) ostatniego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metoda


Określa indeks ostatniego wystąpienia określonego elementu w tablicy.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ArrayType | Typ elementów w docelowej tablicy |
| ValueType | typ elementu, którego szukamy w tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) do przeszukania określonego elementu w |
| value | const [ValueType](../valuetype/)\& | Indeks elementu, którego pozycja ma zostać określona |

### Wartość zwracana

[Index](../../index/) ostatniego wystąpienia określonego elementu, jeśli element zostanie znaleziony, w przeciwnym razie -1

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)