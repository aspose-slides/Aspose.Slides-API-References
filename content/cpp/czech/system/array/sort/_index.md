---
title: Sort()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Řadí prvky ve specifikovaném poli pomocí výchozího porovnávače.
type: docs
weight: 742
url: /cs/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metoda

Řadí prvky ve specifikovaném poli pomocí výchozího porovnávače.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cílové pole |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metoda

Řadí rozsah prvků ve specifikovaném poli pomocí výchozího porovnávače.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cílové pole |
| startIndex | int | Index označující začátek rozsahu prvků k řazení |
| count | int | Velikost rozsahu prvků k řazení |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metoda

Řadí prvky ve specifikovaném poli pomocí zadaného porovnávače.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cílové pole |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Objekt IComparer<T> použitý k porovnání prvků pole |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metoda

NEIMPLEMENTOVÁNO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metoda

Řadí prvky ve specifikovaném poli pomocí zadaného porovnání.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metoda

Řadí dvě pole, z nichž jedno obsahuje klíče a druhé odpovídající položky, na základě hodnot pole obsahujícího klíče, jehož prvky jsou porovnávány pomocí operátoru <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ prvků v poli **keys** |
| TValue | Typ prvků v poli **items** |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) která obsahuje hodnoty klíčů |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) která obsahuje položky, které jsou přiřazeny k hodnotám klíčů v poli **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metoda

Řadí dvě pole, z nichž jedno obsahuje klíče a druhé odpovídající položky, na základě hodnot pole obsahujícího klíče, jehož prvky jsou porovnávány pomocí výchozího porovnávače.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ prvků v poli **keys** |
| TValue | Typ prvků v poli **items** |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) která obsahuje hodnoty klíčů |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) která obsahuje položky, které jsou přiřazeny k hodnotám klíčů v poli **keys** |
| index | int | Index označující začátek rozsahu k řazení |
| length | int | Počet prvků v rozsahu k řazení |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)