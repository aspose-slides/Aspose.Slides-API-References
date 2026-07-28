---
title: Sort()
second_title: Aspose.Slides dla C++ – Referencja API
description: Sortuje elementy w określonej tablicy przy użyciu domyślnego komparatora.
type: docs
weight: 742
url: /pl/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metoda


Sortuje elementy w określonej tablicy przy użyciu domyślnego komparatora.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tablica docelowa |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metoda


Sortuje zakres elementów w określonej tablicy przy użyciu domyślnego komparatora.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tablica docelowa |
| startIndex | int | Indeks określający początek zakresu elementów do sortowania |
| count | int | Rozmiar zakresu elementów do sortowania |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metoda


Sortuje elementy w określonej tablicy przy użyciu określonego komparatora.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tablica docelowa |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Obiekt IComparer<T> używany do porównywania elementów tablicy |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metoda


NIE ZAIMPLEMENTOWANO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metoda


Sortuje elementy w określonej tablicy przy użyciu określonego porównania.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metoda


Sortuje dwie tablice, jedną zawierającą klucze i drugą – odpowiadające elementy, na podstawie wartości tablicy zawierającej klucze, których elementy są porównywane przy użyciu operatora <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ elementów w tablicy **keys** |
| TValue | Typ elementów w tablicy **items** |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) zawierający wartości kluczy |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) zawierający elementy, które są mapowane do wartości kluczy w tablicy **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metoda


Sortuje dwie tablice, jedną zawierającą klucze i drugą – odpowiadające elementy, na podstawie wartości tablicy zawierającej klucze, których elementy są porównywane przy użyciu domyślnego komparatora.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ elementów w tablicy **keys** |
| TValue | Typ elementów w tablicy **items** |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) zawierający wartości kluczy |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) zawierający elementy, które są mapowane do wartości kluczy w tablicy **keys** |
| index | int | Indeks określający początek zakresu do posortowania |
| length | int | Liczba elementów w zakresie do posortowania |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Metoda [Type](../../object/type/)
* Klasa [Array](../)
* Klasa [IComparer](../../../system.collections.generic/icomparer/)
* Klasa [Comparison](../../comparison/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)