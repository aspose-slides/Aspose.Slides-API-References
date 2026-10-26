---
title: NotNullAreNotEqual()
second_title: Aspose.Slides for C++ API Referencia
description: Az egyenlőtlenség-összehasonlítás értéktípusú szótárakat hajt végre.
type: docs
weight: 118
url: /hu/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás szótárakat értéktípusok esetén.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás szótárakat megosztott mutatókkal.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás halmazokat.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal konténer elem típusa. |
| T2 | Jobb oldal konténer elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás sorokat.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal konténer elem típusa. |
| T2 | Jobb oldal konténer elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás veremeket.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal konténer elem típusa. |
| T2 | Jobb oldal konténer elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás rendezett szótárakat értéktípusokkal.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás rendezett szótárakat megosztott mutatókkal.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás rendezett listákat értéktípusokkal.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás rendezett listákat megosztott mutatókkal.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) függvény


Az egyenlőtlenség-összehasonlítás bit tömböket.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) függvény


Az egyenlőtlenség-összehasonlítás karaktergyűjteményeket.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) függvény


Az egyenlőtlenség-összehasonlítás absztrakt gyűjteményeket.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) függvény


Az egyenlőtlenség-összehasonlítás ismeretlen típusokat.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal objektum típusa. |
| T2 | Jobb oldal objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezése. |
| rhs_expr | const char * | Jobb oldal kifejezése. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | Bal oldal értéke. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | Jobb oldal értéke. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Osztály [Dictionary](../../system.collections.generic/dictionary/)
* Osztály [HashSet](../../system.collections.generic/hashset/)
* Osztály [Queue](../../system.collections.generic/queue/)
* Osztály [Stack](../../system.collections.generic/stack/)
* Osztály [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Osztály [SortedList](../../system.collections.generic/sortedlist/)
* Osztály [BitArray](../../system.collections/bitarray/)
* Osztály [StringCollection](../../system.collections.specialized/stringcollection/)
* Osztály [ICollection](../../system.collections.generic/icollection/)
* Névtér [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)