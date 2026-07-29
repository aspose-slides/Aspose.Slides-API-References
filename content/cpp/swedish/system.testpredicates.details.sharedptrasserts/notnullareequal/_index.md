---
title: NotNullAreEqual()
second_title: Aspose.Slides för C++ API-referens
description: Jämför ordböcker av värdetyper för likhet.
type: docs
weight: 53
url: /sv/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

Jämför ordböcker av värdetyper för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

Jämför ordböcker av delade pekare för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

Jämför hashset för likhet.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster behållarelementtyp. |
| T2 | Höger behållarelementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

Jämför köer för likhet.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster behållarelementtyp. |
| T2 | Höger behållarelementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

Jämför stackar för likhet.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster behållarelementtyp. |
| T2 | Höger behållarelementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

Jämför sorterade ordböcker av värdetyper för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

Jämför sorterade ordböcker av delade pekare för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

Jämför sorterade listor av värdetyper för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

Jämför sorterade listor av delade pekare för likhet.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

Jämför bitfält för likhet.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

Jämför strängsamlingar för likhet.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

Jämför abstrakta samlingar för likhet.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function

Jämför två [Object](../../system/object/) typer för likhet.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

Jämför okända typer för likhet.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Vänster objekttyp. |
| T2 | Höger objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | Vänster värde. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | Höger värde. |

### Returvärde

gtest-styled assertion result.

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
* Klass [Object](../../system/object/)
* Namnrymd [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotek [Aspose.Slides](../../)