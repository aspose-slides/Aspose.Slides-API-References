---
title: NotNullAreNotEqual()
second_title: Aspose.Slides for C++ API 參考
description: 不相等比較值型別的字典。
type: docs
weight: 118
url: /zh-hant/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

不相等比較值型別的字典。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

不相等比較共享指標的字典。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

不相等比較雜湊集合。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側容器元素型別。 |
| T2 | 右側容器元素型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

不相等比較佇列。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側容器元素型別。 |
| T2 | 右側容器元素型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

不相等比較堆疊。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側容器元素型別。 |
| T2 | 右側容器元素型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

不相等比較已排順的值型別字典。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

不相等比較已排順的共享指標字典。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

Npt=equal-比較已排序的值型別列表。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

不相等比較已排順的共享指標列表。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵型別。 |
| V | 值型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

不相等比較位元組陣列。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

不相等比較字串集合。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

不相等比較抽象集合。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 元素型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

不相等比較未知類型。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件型別。 |
| T2 | 右側物件型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* 類別 [Dictionary](../../system.collections.generic/dictionary/)
* 類別 [HashSet](../../system.collections.generic/hashset/)
* 類別 [Queue](../../system.collections.generic/queue/)
* 類別 [Stack](../../system.collections.generic/stack/)
* 類別 [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* 類別 [SortedList](../../system.collections.generic/sortedlist/)
* 類別 [BitArray](../../system.collections/bitarray/)
* 類別 [StringCollection](../../system.collections.specialized/stringcollection/)
* 類別 [ICollection](../../system.collections.generic/icollection/)
* 命名空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)