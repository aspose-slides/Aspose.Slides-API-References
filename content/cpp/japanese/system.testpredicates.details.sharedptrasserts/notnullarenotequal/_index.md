---
title: NotNullAreNotEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: 等価でない比較は、値型のディクショナリを比較します。
type: docs
weight: 118
url: /ja/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

等価でない比較は、値型のディクショナリを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

等価でない比較は、共有ポインタのディクショナリを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

等価でない比較は、ハッシュセットを比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺コンテナ要素型。 |
| T2 | 右辺コンテナ要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

等価でない比較は、キューを比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺コンテナ要素型。 |
| T2 | 右辺コンテナ要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

等価でない比較は、スタックを比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺コンテナ要素型。 |
| T2 | 右辺コンテナ要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

等価でない比較は、値型のソートされたディクショナリを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

等価でない比較は、共有ポインタのソートされたディクショナリを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

等価でない比較は、値型のソートされたリストを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

等価でない比較は、共有ポインタのソートされたリストを比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キー型。 |
| V | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

等価でない比較は、ビット配列を比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

等価でない比較は、文字列コレクションを比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

等価でない比較は、抽象コレクションを比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

等価でない比較は、未知の型を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺オブジェクト型。 |
| T2 | 右辺オブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | 右辺の値。 |

### 戻り値

gtest-styled assertion result.

## 参照

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [Dictionary](../../system.collections.generic/dictionary/)
* クラス [HashSet](../../system.collections.generic/hashset/)
* クラス [Queue](../../system.collections.generic/queue/)
* クラス [Stack](../../system.collections.generic/stack/)
* クラス [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* クラス [SortedList](../../system.collections.generic/sortedlist/)
* クラス [BitArray](../../system.collections/bitarray/)
* クラス [StringCollection](../../system.collections.specialized/stringcollection/)
* クラス [ICollection](../../system.collections.generic/icollection/)
* 名前空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* ライブラリ [Aspose.Slides](../../)