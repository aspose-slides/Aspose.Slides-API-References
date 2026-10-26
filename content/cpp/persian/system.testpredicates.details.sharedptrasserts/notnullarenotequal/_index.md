---
title: NotNullAreNotEqual()
second_title: Aspose.Slides برای C++ مرجع API
description: مقایسه نابرابر دیکشنری‌های نوع مقدار.
type: docs
weight: 118
url: /fa/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) تابع

مقایسه نابرابر دیکشنری‌های نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) تابع

مقایسه نابرابر دیکشنری‌های اشاره‌گرهای اشتراکی.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) تابع

مقایسه نابرابر مجموعه‌های هش.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عنصر سمت چپ. |
| T2 | نوع عنصر سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) تابع

مقایسه نابرابر صف‌ها.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عنصر سمت چپ. |
| T2 | نوع عنصر سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) تابع

مقایسه نابرابر پشته‌ها.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عنصر سمت چپ. |
| T2 | نوع عنصر سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) تابع

مقایسه نابرابر دیکشنری‌های مرتب‌شده از نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) تابع

مقایسه نابرابر دیکشنری‌های مرتب‌شده از اشاره‌گرهای اشتراکی.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) تابع

مقایسه نابرابر فهرست‌های مرتب‌شده از نوع مقدار.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) تابع

مقایسه نابرابر فهرست‌های مرتب‌شده از اشاره‌گرهای اشتراکی.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) تابع

مقایسه نابرابر آرایه‌های بیتی.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) تابع

مقایسه نابرابر مجموعه‌های رشته‌ای.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) تابع

مقایسه نابرابر مجموعه‌های انتزاعی.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) تابع

مقایسه نابرابر انواع ناشناخته.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء سمت چپ. |
| T2 | نوع شیء سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | مقدار سمت چپ. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | مقدار سمت راست. |

### مقدار بازگشتی

نتیجهٔ ادعا به سبک gtest.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../system/sharedptr/)
* کلاس [Dictionary](../../system.collections.generic/dictionary/)
* کلاس [HashSet](../../system.collections.generic/hashset/)
* کلاس [Queue](../../system.collections.generic/queue/)
* کلاس [Stack](../../system.collections.generic/stack/)
* کلاس [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* کلاس [SortedList](../../system.collections.generic/sortedlist/)
* کلاس [BitArray](../../system.collections/bitarray/)
* کلاس [StringCollection](../../system.collections.specialized/stringcollection/)
* کلاس [ICollection](../../system.collections.generic/icollection/)
* فضای‌نام [System::TestPredicates::Details::SharedPtrAsserts](../)
* کتابخانه [Aspose.Slides](../../)