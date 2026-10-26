---
title: NotNullAreEqual()
second_title: مرجع API Aspose.Slides برای C++
description: مقایسه برابری دیکشنری‌های نوع مقدار.
type: docs
weight: 53
url: /fa/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>) function

مقایسه برابری دیکشنری‌های نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>) function

مقایسه برابری دیکشنری‌های اشاره‌گرهای مشترک.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>) function

مقایسه برابری مجموعه‌های هش.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع عنصر محفظه سمت چپ. |
| T2 | نوع عنصر محفظه سمت راست. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>) function

مقایسه برابری صف‌ها.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع عنصر محفظه سمت چپ. |
| T2 | نوع عنصر محفظه سمت راست. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>) function

مقایسه برابری پشته‌ها.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع عنصر محفظه سمت چپ. |
| T2 | نوع عنصر محفظه سمت راست. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>) function

مقایسه برابری دیکشنری‌های مرتب شده از نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>) function

مقایسه برابری دیکشنری‌های مرتب شده از اشاره‌گرهای مشترک.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>) function

مقایسه برابری فهرست‌های مرتب شده از نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>) function

مقایسه برابری فهرست‌های مرتب شده از اشاره‌گرهای مشترک.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

مقایسه برابری آرایه‌های بیتی.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

مقایسه برابری مجموعه‌های رشته‌ای.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

مقایسه برابری مجموعه‌های انتزاعی.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عنصر. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function

مقایسه برابری دو [Object](../../system/object/) نوع.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

مقایسه برابری انواع نامشخص.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع شی سمت چپ. |
| T2 | نوع شی سمت راست. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | مقدار سمت راست. |

### مقدار بازگشت

gtest-styled assertion result.

## همچنین ببینید

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