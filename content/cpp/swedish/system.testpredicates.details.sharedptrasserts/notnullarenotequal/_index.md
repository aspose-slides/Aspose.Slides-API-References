---
title: NotNullAreNotEqual()
second_title: Aspose.Slides för C++ API-referens
description: Inte-lika-jämför dictionaries av värdetyper.
type: docs
weight: 118
url: /sv/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function


Inte-lika-jämför dictionaries av värdetyper.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function


Inte-lika-jämför dictionaries av delade pekare.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function


Inte-lika-jämför hashset.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster-sida-behållarens elementtyp. |
| T2 | Höger-sida-behållarens elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function


Inte-lika-jämför köer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster-sida-behållarens elementtyp. |
| T2 | Höger-sida-behållarens elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function


Inte-lika-jämför stackar.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster-sida-behållarens elementtyp. |
| T2 | Höger-sida-behållarens elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function


Inte-lika-jämför sorterade dictionarys av värdetyper.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function


Inte-lika-jämför sorterade dictionarys av delade pekare.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function


Inte-lika-jämför sorterade listor av värdetyper.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function


Inte-lika-jämför sorterade listor av delade pekare.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function


Inte-lika-jämför bit-arrayer.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function


Inte-lika-jämför strängsamlingar.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function


Inte-lika-jämför abstrakta samlingar.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function


Inte-lika-jämför okända typer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster-sida-objekttyp. |
| T2 | Höger-sida-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster-sida-uttryck. |
| rhs_expr | const char * | Höger-sida-uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | Vänster-sida-värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | Höger-sida-värde. |

### Returvärde

gtest-stylat assertionsresultat.

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [Dictionary](../../system.collections.generic/dictionary/)
* Klass [HashSet](../../system.collections.generic/hashset/)
* Klass [Queue](../../system.collections.generic/queue/)
* Klass [Stack](../../system.collections.generic/stack/)
* Klass [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Klass [SortedList](../../system.collections.generic/sortedlist/)
* Klass [BitArray](../../system.collections/bitarray/)
* Klass [StringCollection](../../system.collections.specialized/stringcollection/)
* Klass [ICollection](../../system.collections.generic/icollection/)
* Namnrymd [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotek [Aspose.Slides](../../)