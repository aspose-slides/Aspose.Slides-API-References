---
title: AreEqual()
second_title: Reference API Aspose.Slides pro C++
description: Porovnává pole neukazatelů.
type: docs
weight: 1
url: /cs/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) metoda

Porovnává pole neukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ prvku pole. |
| U | Druhý typ prvku pole. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Levé pole. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Pravé pole. |

### Návratová hodnota

true if arrays sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) metoda

Porovnává pole ukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ ukazovaného prvku pole. |
| U | Druhý typ ukazovaného prvku pole. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Levé pole. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravé pole. |

### Návratová hodnota

true if arrays sizes and objects match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metoda

Porovnává seznamy neukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ prvku seznamu. |
| U | Druhý typ prvku seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Levý seznam. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Pravý seznam. |

### Návratová hodnota

true if sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metoda

Porovnává seznamy ukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ ukazovaného prvku seznamu. |
| U | Druhý typ ukazovaného prvku seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Levý seznam. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý seznam. |

### Návratová hodnota

true if lists sizes and objects match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) metoda

Porovnává seznamy s poli v případě prvků, které nejsou ukazatele.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvku seznamu. |
| U | [Array](../../array/) typ prvku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Seznam. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Návratová hodnota

true if sizes and data match, false otherwise.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metoda

Porovnává seznamy s poli v případě prvků, které nejsou ukazatele.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Array](../../array/) typ prvku. |
| U | Typ prvku seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Seznam. |

### Návratová hodnota

true if sizes and data match, false otherwise.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metoda

Porovnává seznamy s poli v případě prvků, které jsou ukazatele.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Array](../../array/) typ ukazovaného prvku. |
| U | Typ ukazovaného prvku seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Seznam. |

### Návratová hodnota

true if sizes and objects match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) metoda

Porovnává seznamy s poli v případě prvků, které jsou ukazatele.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ ukazovaného prvku seznamu. |
| U | [Array](../../array/) typ ukazovaného prvku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Seznam. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Návratová hodnota

true if sizes and objects match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) metoda

Porovnává slovníky s typy, které nejsou ukazatelé.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Pravý slovník. |

### Návratová hodnota

true if dictionaries sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) metoda

Porovnává slovníky s typy, které jsou ukazatele.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý slovník. |

### Návratová hodnota

true if dictionaries sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) metoda

Porovnává slovníky různých typů.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K1 | Typ klíče levého slovníku. |
| U1 | Typ mapovaného prvku levého slovníku. |
| K2 | Typ klíče pravého slovníku. |
| U2 | Typ mapovaného prvku pravého slovníku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Pravý slovník. |

### Návratová hodnota

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) metoda

Porovnává hashsety neukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ prvku hashsetu. |
| U | Druhý typ prvku hashsetu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Levý hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Pravý hashset. |

### Návratová hodnota

true if hashsets sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) metoda

Porovnává hashsety ukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ ukazovaného prvku hashsetu. |
| U | Druhý typ ukazovaného prvku hashsetu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Levý hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý hashset. |

### Návratová hodnota

true if hashsets sizes and data match, false otherwise.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) metoda

Porovnává fronty neukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ prvku fronty. |
| U | Druhý typ prvku fronty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Levá fronta. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Pravá fronta. |

### Návratová hodnota

true if queues sizes and data match, false otherwise.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) metoda

Porovnává fronty ukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ ukazovaného prvku fronty. |
| U | Druhý typ ukazovaného prvku fronty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Levá fronta. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Pravá fronta. |

### Návratová hodnota

true if queues sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) metoda

Porovnává zásobníky neukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ prvku zásobníku. |
| U | Druhý typ prvku zásobníku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Levý zásobník. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Pravý zásobník. |

### Návratová hodnota

true if stacks sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) metoda

Porovnává zásobníky ukazatelů.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | První typ ukazovaného prvku zásobníku. |
| U | Druhý typ ukazovaného prvku zásobníku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Levý zásobník. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý zásobník. |

### Návratová hodnota

true if stacks sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) metoda

Porovnává setříděné slovníky s typy, které nejsou ukazatelé.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Pravý slovník. |

### Návratová hodnota

true if dictionaries sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) metoda

Porovnává setříděné slovníky s typy, které jsou ukazatele.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý slovník. |

### Návratová hodnota

true if dictionaries sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) metoda

Porovnává setříděné slovníky různých typů.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K1 | Typ klíče levého slovníku. |
| U1 | Typ mapovaného prvku levého slovníku. |
| K2 | Typ klíče pravého slovníku. |
| U2 | Typ mapovaného prvku pravého slovníku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Levý slovník. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Pravý slovník. |

### Návratová hodnota

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) metoda

Porovnává setříděné seznamy s typy, které nejsou ukazatelé.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Levý seznam. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Pravý seznam. |

### Návratová hodnota

true if lists sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) metoda

Porovnává setříděné seznamy s typy, které jsou ukazatele.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Typ klíče. |
| U | Mapovaný typ ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Levý seznam. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pravý seznam. |

### Návratová hodnota

true if lists sizes and data match, false otherwise.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) metoda

Porovnává setříděné seznamy různých typů.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K1 | Typ klíče levého seznamu. |
| U1 | Typ mapovaného prvku levého seznamu. |
| K2 | Typ klíče pravého seznamu. |
| U2 | Typ mapovaného prvku pravého seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Levý seznam. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Pravý seznam. |

### Návratová hodnota

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) metoda

Porovnává kolekce řetězců.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Levá kolekce. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Pravá kolekce. |

### Návratová hodnota

True if sizes and data match, false otherwise.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) metoda

Porovnává instance IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Levý enumerable objekt. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Pravý enumerable objekt. |

### Návratová hodnota

True if sizes and data match, false otherwise.

## Viz také

* Definice typu [SharedPtr](../../sharedptr/)
* Definice typu [ArrayPtr](../../arrayptr/)
* Třída [Array](../../array/)
* Třída [List](../../../system.collections.generic/list/)
* Třída [Dictionary](../../../system.collections.generic/dictionary/)
* Třída [HashSet](../../../system.collections.generic/hashset/)
* Třída [QueuePtr](../../../system.collections.generic/queueptr/)
* Třída [Stack](../../../system.collections.generic/stack/)
* Třída [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Třída [SortedList](../../../system.collections.generic/sortedlist/)
* Třída [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktura [TestCompare](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)