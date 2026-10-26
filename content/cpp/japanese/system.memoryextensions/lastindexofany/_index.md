---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API リファレンス
description: span 内で指定された3つの値のいずれかが最後に出現する位置を検索します。
type: docs
weight: 222
url: /ja/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 関数

指定された3つの値のいずれかが span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象の span |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する2番目の値 |
| value2 | const T\& | 検索する3番目の値 |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 関数

指定された3つの値のいずれかが変更可能な span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の span |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する2番目の値 |
| value2 | const T\& | 検索する3番目の値 |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された2つの値のいずれかが span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象の span |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する2番目の値 |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) 関数

指定された2つの値のいずれかが変更可能な span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の span |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する2番目の値 |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

シーケンスから任意の値が span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象の span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する値のシーケンス |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

シーケンスから任意の値が変更可能な span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する値のシーケンス |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) 関数

変更可能なシーケンスから任意の値が変更可能な span 内で最後に出現する位置を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | span 内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の span |
| values | const [Span](../../system/span/)\<T\>\& | 検索する値のシーケンス |

### 戻り値

最後に出現した位置の0ベースインデックス。見つからない場合は -1 を返します。

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)