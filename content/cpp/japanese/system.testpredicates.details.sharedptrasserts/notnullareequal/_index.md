---
title: NotNullAreEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: 値型のディクショナリを等価比較します。
type: docs
weight: 53
url: /ja/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

値型のディクショナリを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

共有ポインタのディクショナリを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

ハッシュセットを等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 左側コンテナ要素型 |
| T2 | 右側コンテナ要素型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

キューを等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 左側コンテナ要素型 |
| T2 | 右側コンテナ要素型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

スタックを等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 左側コンテナ要素型 |
| T2 | 右側コンテナ要素型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

値型のソート済みディクショナリを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

共有ポインタのソート済みディクショナリを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

値型のソート済みリストを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

共有ポインタのソート済みリストを等価比較します。

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型 |
| V | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

ビット配列を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

文字列コレクションを等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

抽象コレクションを等価比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 要素型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function

[Object](../../system/object/) 型の 2 つを等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

不明な型を等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 左側オブジェクト型 |
| T2 | 右側オブジェクト型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側式 |
| rhs_expr | const char * | 右側式 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | 左側値 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | 右側値 |

### 戻り値

gtest 形式のアサーション結果です。

## 参照

* Typedef [SharedPtr](../../system/sharedptr/)
* クラス [Dictionary](../../system.collections.generic/dictionary/)
* クラス [HashSet](../../system.collections.generic/hashset/)
* クラス [Queue](../../system.collections.generic/queue/)
* クラス [Stack](../../system.collections.generic/stack/)
* クラス [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* クラス [SortedList](../../system.collections.generic/sortedlist/)
* クラス [BitArray](../../system.collections/bitarray/)
* クラス [StringCollection](../../system.collections.specialized/stringcollection/)
* クラス [ICollection](../../system.collections.generic/icollection/)
* クラス [Object](../../system/object/)
* 名前空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* ライブラリ [Aspose.Slides](../../)