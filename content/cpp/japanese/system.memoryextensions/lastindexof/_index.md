---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: スパン内でシーケンスの最後の出現を検索します。
type: docs
weight: 209
url: /ja/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

スパン内でシーケンスの最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索するシーケンス |

### 戻り値

最後の出現のゼロベースインデックス、見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) 関数

スパン内で単一の値の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索する値 |

### 戻り値

最後の出現のゼロベースインデックス、見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

可変スパン内でシーケンスの最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索するシーケンス |

### 戻り値

最後の出現のゼロベースインデックス、見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) 関数

可変スパン内で単一の値の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索する値 |

### 戻り値

最後の出現のゼロベースインデックス、見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数

指定された文字列比較を使用して、スパン内で値の最後の出現を検索します。

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索する値 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 実行する文字列比較の種類 |

### 戻り値

最後の出現のゼロベースインデックス、見つからない場合は -1 を返します。

## 参照

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)