---
title: Sort()
second_title: Aspose.Slides för C++ API-referens
description: Sorterar element i den angivna arrayen med standardjämförare.
type: docs
weight: 742
url: /sv/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metod

Sorterar element i den angivna arrayen med standardjämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Målarray |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metod

Sorterar ett intervall av element i den angivna arrayen med standardjämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Målarray |
| startIndex | int | Index som anger början av intervallet av element som ska sorteras |
| count | int | Storleken på intervallet av element som ska sorteras |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metod

Sorterar element i den angivna arrayen med angiven jämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Målarray |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T>-objekt som används för att jämföra element i arrayen |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metod

INTE IMPLEMENTERAD.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metod

Sorterar element i den angivna arrayen med angiven jämförelse.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metod

Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, där elementen jämförs med operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av elementen i **keys**-arrayen |
| TValue | Typen av elementen i **items**-arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) som innehåller nyckelvärden |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) som innehåller objekt som är mappade till nyckelvärdena i **keys**-arrayen |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metod

Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, där elementen jämförs med standardjämförare.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av elementen i **keys**-arrayen |
| TValue | Typen av elementen i **items**-arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) som innehåller nyckelvärden |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) som innehåller objekt som är mappade till nyckelvärdena i **keys**-arrayen |
| index | int | Index som anger början av intervallet som ska sorteras |
| length | int | Antalet element i intervallet som ska sorteras |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)