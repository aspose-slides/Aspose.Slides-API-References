---
title: BinarySearch()
second_title: Aspose.Slides for C++ API リファレンス
description: ソートされたスパンで二分探索を実行します。
type: docs
weight: 14
url: /ja/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) 関数

ソートされたスパンで二分探索を実行します。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TComparable | 比較可能な値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のソートされたスパン |
| comparable | const TComparable\& | 検索する値 |

### 戻り値

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 関数

カスタム比較子を使用して、ソートされたスパンで二分探索を実行します。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TComparer | 比較子の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のソートされたスパン |
| value | const T\& | 検索する値 |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 比較に使用する比較子 |

### 戻り値

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) 関数

変更可能なソート済みスパンで二分探索を実行します。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TComparable | 比較可能な値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のソートされたスパン |
| comparable | const TComparable\& | 検索する値 |

### 戻り値

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 関数

カスタム比較子を使用して、変更可能なソート済みスパンで二分探索を実行します。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TComparer | 比較子の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のソートされたスパン |
| value | const T\& | 検索する値 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 比較に使用する比較子 |

### 戻り値

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## 参照

* typedef [SharedPtr](../../system/sharedptr/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)