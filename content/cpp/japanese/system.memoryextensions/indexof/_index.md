---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: ReadOnlySpan<T> の値が別の ReadOnlySpan<T> にあるインデックスを検索します
type: docs
weight: 144
url: /ja/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


ReadOnlySpan<T> の値が別の ReadOnlySpan<T> にあるインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |

### 戻り値

最初に見つかった位置のゼロベースインデックス、または見つからなければ -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) 関数


ReadOnlySpan<T> 内の単一の値のインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索対象の値 |

### 戻り値

最初に見つかった位置のゼロベースインデックス、または見つからなければ -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


ReadOnlySpan<T> の値が Span<T> にあるインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |

### 戻り値

最初に見つかった位置のゼロベースインデックス、または見つからなければ -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) 関数


Span<T> 内の単一の値のインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索対象の値 |

### 戻り値

最初に見つかった位置のゼロベースインデックス、または見つからなければ -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数


StringComparison を使用して ReadOnlySpan<char16_t> の値が別の ReadOnlySpan<char16_t> にあるインデックスを検索します。

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索対象の値 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 使用する文字列比較の種類 |

### 戻り値

最初に見つかった位置のゼロベースインデックス、または見つからなければ -1

## 参照

* 列挙体 [StringComparison](../../system/stringcomparison/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)