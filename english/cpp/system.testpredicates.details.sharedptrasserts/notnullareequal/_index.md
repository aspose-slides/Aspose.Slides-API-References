---
title: NotNullAreEqual()
second_title: Aspose.Slides for C++ API Reference
description: Equal-compares dictionaries of value types.
type: docs
weight: 53
url: /cpp/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function


Equal-compares dictionaries of value types.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function


Equal-compares dictionaries of shared pointers.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function


Equal-compares hashsets.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS container element type. |
| T2 | RHS container element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function


Equal-compares queues.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS container element type. |
| T2 | RHS container element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function


Equal-compares stacks.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS container element type. |
| T2 | RHS container element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function


Equal-compares sorted dictionaries of value types.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function


Equal-compares sorted dictionaries of shared pointers.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function


Equal-compares sorted lists of value types.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function


Equal-compares sorted lists of shared pointers.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function


Equal-compares bit arrays.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function


Equal-compares string collections.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function


Equal-compares abstract collections.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function


Equal-compares two [Object](../../system/object/) types.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function


Equal-compares unknown types.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | RHS value. |

### Return Value

gtest-styled assertion result.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Dictionary](../../system.collections.generic/dictionary/)
* Class [HashSet](../../system.collections.generic/hashset/)
* Class [Queue](../../system.collections.generic/queue/)
* Class [Stack](../../system.collections.generic/stack/)
* Class [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../system.collections.generic/sortedlist/)
* Class [BitArray](../../system.collections/bitarray/)
* Class [StringCollection](../../system.collections.specialized/stringcollection/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Class [Object](../../system/object/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)