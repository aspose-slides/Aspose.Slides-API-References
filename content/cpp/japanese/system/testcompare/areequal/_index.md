---
title: AreEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: ポインタでない配列を比較します。
type: docs
weight: 1
url: /ja/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

ポインタでない配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初の配列要素型。 |
| U | 第二の配列要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 左辺配列。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | 右辺配列。 |

### 戻り値

配列のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

ポインタ配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初の配列が指す型。 |
| U | 第二の配列が指す型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左辺配列。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺配列。 |

### 戻り値

配列のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

ポインタでないリストを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のリスト要素型。 |
| U | 第二のリスト要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 左辺リスト。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 右辺リスト。 |

### 戻り値

リストのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

ポインタリストを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のリストが指す型。 |
| U | 第二のリストが指す型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左辺リスト。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺リスト。 |

### 戻り値

リストのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

ポインタでない要素の場合のリストと配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | リスト要素型。 |
| U | [Array](../../array/) 要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | リスト。 |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/)。 |

### 戻り値

サイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

ポインタでない要素の場合のリストと配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Array](../../array/) 要素型。 |
| U | リスト要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/)。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | リスト。 |

### 戻り値

サイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

ポインタ要素の場合のリストと配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Array](../../array/) 参照先型。 |
| U | リストの参照先型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/)。 |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | リスト。 |

### 戻り値

サイズとオブジェクトが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

ポインタ要素の場合のリストと配列を比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | リストの参照先型。 |
| U | [Array](../../array/) 参照先型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | リスト。 |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/)。 |

### 戻り値

サイズとオブジェクトが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

ポインタでないマッピング型の辞書を比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 右辺辞書。 |

### 戻り値

辞書のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

ポインタマッピング型の辞書を比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピングされた参照先型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺辞書。 |

### 戻り値

辞書のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

異なる型の辞書を比較します。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K1 | 左辺辞書のキー型。 |
| U1 | 左辺辞書のマッピング型。 |
| K2 | 右辺辞書のキー型。 |
| U2 | 右辺辞書のマッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | 右辺辞書。 |

### 戻り値

型変換はここでは禁止されているため、常に false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

ポインタでないハッシュセットを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のハッシュセット要素型。 |
| U | 第二のハッシュセット要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | 左辺ハッシュセット。 |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | 右辺ハッシュセット。 |

### 戻り値

ハッシュセットのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

ポインタハッシュセットを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のハッシュセットが指す型。 |
| U | 第二のハッシュセットが指す型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左辺ハッシュセット。 |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺ハッシュセット。 |

### 戻り値

ハッシュセットのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

ポインタでないキューを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のキュー要素型。 |
| U | 第二のキュー要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | 左辺キュー。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | 右辺キュー。 |

### 戻り値

キューのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

ポインタキューを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のキューが指す型。 |
| U | 第二のキューが指す型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | 左辺キュー。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | 右辺キュー。 |

### 戻り値

キューのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

ポインタでないスタックを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のスタック要素型。 |
| U | 第二のスタック要素型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | 左辺スタック。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | 右辺スタック。 |

### 戻り値

スタックのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

ポインタスタックを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 最初のスタックが指す型。 |
| U | 第二のスタックが指す型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左辺スタック。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺スタック。 |

### 戻り値

スタックのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

ポインタでないマッピング型のソート済み辞書を比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 右辺辞書。 |

### 戻り値

辞書のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

ポインタマッピング型のソート済み辞書を比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピングされた参照先型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺辞書。 |

### 戻り値

辞書のサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

異なる型のソート済み辞書を比較します。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K1 | 左辺辞書キー型。 |
| U1 | 左辺辞書マッピング型。 |
| K2 | 右辺辞書キー型。 |
| U2 | 右辺辞書マッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | 左辺辞書。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | 右辺辞書。 |

### 戻り値

型変換はここでは禁止されているため、常に false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

ポインタでないマッピング型のソート済みリストを比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 左辺リスト。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 右辺リスト。 |

### 戻り値

リストのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

ポインタマッピング型のソート済みリストを比較します。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K | キー型。 |
| U | マッピングされた参照先型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左辺リスト。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右辺リスト。 |

### 戻り値

リストのサイズとデータが一致すれば true、そうでなければ false を返します。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

異なる型のソート済みリストを比較します。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| K1 | 左辺リストキー型。 |
| U1 | 左辺リストマッピング型。 |
| K2 | 右辺リストキー型。 |
| U2 | 右辺リストマッピング型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | 左辺リスト。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | 右辺リスト。 |

### 戻り値

型変換はここでは禁止されているため、常に false を返します。

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

文字列コレクションを比較します。

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 左辺コレクション。 |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 右辺コレクション。 |

### 戻り値

サイズとデータが一致すれば True、そうでなければ false を返します。

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

IEnumerable インスタンスを比較します。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 左辺列挙可能オブジェクト。 |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | 右辺列挙可能オブジェクト。 |

### 戻り値

サイズとデータが一致すれば True、そうでなければ false を返します。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [Array](../../array/)
* クラス [List](../../../system.collections.generic/list/)
* クラス [Dictionary](../../../system.collections.generic/dictionary/)
* クラス [HashSet](../../../system.collections.generic/hashset/)
* クラス [QueuePtr](../../../system.collections.generic/queueptr/)
* クラス [Stack](../../../system.collections.generic/stack/)
* クラス [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* クラス [SortedList](../../../system.collections.generic/sortedlist/)
* クラス [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* 構造体 [TestCompare](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)