---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 2 つのスパン間の共通プレフィックスの長さを取得します。
type: docs
weight: 27
url: /ja/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

2つのスパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 最初のスパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 2 番目のスパン |

### 戻り値

両方のスパンの先頭で一致する要素の数

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

可変スパンと読み取り専用スパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可変スパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 読み取り専用スパン |

### 戻り値

両方のスパンの先頭で一致する要素の数

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) 関数

2 つの可変スパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 最初の可変スパン |
| other | const [Span](../../system/span/)\<T\>\& | 2 番目の可変スパン |

### 戻り値

両方のスパンの先頭で一致する要素の数

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 関数

カスタム等価比較子を使用して 2 つのスパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TEqualityComparer | 等価比較子の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 最初のスパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 2 番目のスパン |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 要素比較に使用する等価比較子 |

### 戻り値

両方のスパンの先頭で一致する要素の数

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 関数

カスタム等価比較子を使用して可変スパンと読み取り専用スパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TEqualityComparer | 等価比較子の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可変スパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 読み取り専用スパン |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 要素比較に使用する等価比較子 |

### 戻り値

両方のスパンの先頭で一致する要素の数

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 関数

カスタム等価比較子を使用して 2 つの可変スパン間の共通プレフィックスの長さを取得します。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TEqualityComparer | 等価比較子の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 最初の可変スパン |
| other | const [Span](../../system/span/)\<T\>\& | 2 番目の可変スパン |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 要素比較に使用する等価比較子 |

### 戻り値

両方のスパンの先頭で一致する要素の数

## 参照

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)