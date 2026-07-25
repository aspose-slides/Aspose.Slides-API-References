---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API リファレンス
description: ReadOnlySpan<T> 内の 2 つの指定された値のいずれかが最初に出現するインデックスを取得します
type: docs
weight: 157
url: /ja/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ReadOnlySpan<T> 内で 2 つの指定された値のいずれかが最初に出現するインデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

ReadOnlySpan<T> 内で 3 つの指定された値のいずれかが最初に出現するインデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |
| value2 | const T\& | 検索する 3 番目の値 |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

Span<T> 内で 2 つの指定された値のいずれかが最初に出現するインデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Span<T> 内で 3 つの指定された値のいずれかが最初に出現するインデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |
| value2 | const T\& | 検索する 3 番目の値 |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

ReadOnlySpan<T> から別の ReadOnlySpan<T> 内の任意の値の最初の出現インデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する値を含むスパン |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Span<T> 内で ReadOnlySpan<T> から任意の値の最初の出現インデックスを取得します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する値を含むスパン |

### 戻り値

最初の出現の 0 始まりインデックス、見つからない場合は -1 を返します

## 関連項目

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)