---
title: AreEqual()
second_title: Aspose.Slides C++ API referenciája
description: Összehasonlítja a nem mutatókat tartalmazó tömböket.
type: docs
weight: 1
url: /hu/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) metódus

Összehasonlítja a nem mutatókat tartalmazó tömböket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első tömb elemtípusa. |
| U | A második tömb elemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Bal oldali tömb. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Jobb oldali tömb. |

### Visszatérési érték

true, ha a tömbök mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) metódus

Összehasonlítja a mutatókat tartalmazó tömböket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első tömb mutatóelemtípusa. |
| U | A második tömb mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Bal oldali tömb. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali tömb. |

### Visszatérési érték

true, ha a tömbök mérete és objektumai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metódus

Összehasonlítja a nem mutatókat tartalmazó listákat.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első lista elem típusa. |
| U | A második lista elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Bal oldali lista. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Jobb oldali lista. |

### Visszatérési érték

true, ha a listák mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metódus

Összehasonlítja a mutatókat tartalmazó listákat.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első lista mutatóelemtípusa. |
| U | A második lista mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Bal oldali lista. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali lista. |

### Visszatérési érték

true, ha a listák mérete és objektumai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) metódus

Összehasonlítja a listákat és a tömböket a nem mutatóelemek esetén.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Lista elem típusa. |
| U | [Array](../../array/) elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Visszatérési érték

true, ha a méretek és adatok egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metódus

Összehasonlítja a listákat és a tömböket a nem mutatóelemek esetén.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Array](../../array/) elem típusa. |
| U | Lista elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Visszatérési érték

true, ha a méretek és adatok egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metódus

Összehasonlítja a listákat és a tömböket a mutatóelemek esetén.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Array](../../array/) mutatóelemtípusa. |
| U | Lista mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Visszatérési érték

true, ha a méretek és objektumok egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) metódus

Összehasonlítja a listákat és a tömböket a mutatóelemek esetén.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Lista mutatóelemtípusa. |
| U | [Array](../../array/) mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Visszatérési érték

true, ha a méretek és objektumok egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) metódus

Összehasonlítja a nem mutatóval leképezett típusú szótárakat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

true, ha a szótárak mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) metódus

Összehasonlítja a mutatóval leképezett típusú szótárakat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

true, ha a szótárak mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) metódus

Összehasonlítja a különböző típusú szótárakat.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K1 | Bal oldali szótár kulcs típusa. |
| U1 | Bal oldali szótár leképezett típusa. |
| K2 | Jobb oldali szótár kulcs típusa. |
| U2 | Jobb oldali szótár leképezett típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

Mindig false, mivel a típuskonverzió itt tiltott.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) metódus

Összehasonlítja a nem mutatókat tartalmazó hashseteket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első hashset elem típusa. |
| U | A második hashset elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Bal oldali hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Jobb oldali hashset. |

### Visszatérési érték

true, ha a hashsetek mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) metódus

Összehasonlítja a mutatókat tartalmazó hashseteket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első hashset mutatóelemtípusa. |
| U | A második hashset mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Bal oldali hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali hashset. |

### Visszatérési érték

true, ha a hashsetek mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) metódus

Összehasonlítja a nem mutatókat tartalmazó sorokat.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első sor elem típusa. |
| U | A második sor elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Bal oldali sor. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Jobb oldali sor. |

### Visszatérési érték

true, ha a sorok mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) metódus

Összehasonlítja a mutatókat tartalmazó sorokat.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első sor mutatóelemtípusa. |
| U | A második sor mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Bal oldali sor. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Jobb oldali sor. |

### Visszatérési érték

true, ha a sorok mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) metódus

Összehasonlítja a nem mutatókat tartalmazó veremeket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első verem elem típusa. |
| U | A második verem elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Bal oldali verem. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Jobb oldali verem. |

### Visszatérési érték

true, ha a veremek mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>) metódus

Összehasonlítja a mutatókat tartalmazó veremeket.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első verem mutatóelemtípusa. |
| U | A második verem mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Bal oldali verem. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali verem. |

### Visszatérési érték

true, ha a veremek mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) metódus

Összehasonlítja a nem mutatóval leképezett típusú rendezett szótárakat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

true, ha a szótárak mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) metódus

Összehasonlítja a mutatóval leképezett típusú rendezett szótárakat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

true, ha a szótárak mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) metódus

Összehasonlítja a különböző típusú rendezett szótárakat.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K1 | Bal oldali szótár kulcs típusa. |
| U1 | Bal oldali szótár leképezett típusa. |
| K2 | Jobb oldali szótár kulcs típusa. |
| U2 | Jobb oldali szótár leképezett típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Bal oldali szótár. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Jobb oldali szótár. |

### Visszatérési érték

Mindig false, mivel a típuskonverzió itt tiltott.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) metódus

Összehasonlítja a nem mutatóval leképezett típusú rendezett listákat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Bal oldali lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Jobb oldali lista. |

### Visszatérési érték

true, ha a listák mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>) metódus

Összehasonlítja a mutatóval leképezett típusú rendezett listákat.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| U | Leképezett mutatóelemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Bal oldali lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Jobb oldali lista. |

### Visszatérési érték

true, ha a listák mérete és adatai egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) metódus

Összehasonlítja a különböző típusú rendezett listákat.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K1 | Bal oldali lista kulcs típusa. |
| U1 | Bal oldali lista leképezett típusa. |
| K2 | Jobb oldali lista kulcs típusa. |
| U2 | Jobb oldali lista leképezett típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Bal oldali lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Jobb oldali lista. |

### Visszatérési érték

Mindig false, mivel a típuskonverzió itt tiltott.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) metódus

Összehasonlítja a karakterlánc-gyűjteményeket.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Bal oldali gyűjtemény. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Jobb oldali gyűjtemény. |

### Visszatérési érték

True, ha a méretek és adatok egyeznek, false ellenkező esetben.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) metódus

Összehasonlítja az IEnumerable példányokat.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Bal oldali felsorolható objektum. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Jobb oldali felsorolható objektum. |

### Visszatérési érték

True, ha a méretek és adatok egyeznek, false ellenkező esetben.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)