---
title: Overlaps()
second_title: Aspose.Slides for C++ API リファレンス
description: オフセットを計算せずに、2 つの ReadOnlySpan がメモリ上で重複しているかどうかを判断します。
type: docs
weight: 274
url: /ja/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

オフセットを計算せずに、2 つの ReadOnlySpan がメモリ上で重複しているかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する最初のスパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する2番目のスパン |

### 戻り値

スパンが共通のメモリ位置を共有している場合は true、そうでない場合は false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

[Span](../../system/span/) と [ReadOnlySpan](../../system/readonlyspan/) がメモリ上で重複しているかどうかを、オフセットを計算せずに判断します。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 重複を確認する [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する [ReadOnlySpan](../../system/readonlyspan/) |

### 戻り値

スパンが共通のメモリ位置を共有している場合は true、そうでない場合は false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 関数

オフセットを計算しながら、2 つの ReadOnlySpan がメモリ上で重複しているかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する最初のスパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する2番目のスパン |
| elementOffset | **int32_t**\& | スパンが重複している場合にオフセットを受け取る出力パラメータ |

### 戻り値

スパンが共通のメモリ位置を共有している場合は true、そうでない場合は false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 関数

[Span](../../system/span/) と [ReadOnlySpan](../../system/readonlyspan/) がメモリ上で重複しているかどうかを判断し、オフセットを計算します。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 重複を確認する [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 重複を確認する [ReadOnlySpan](../../system/readonlyspan/) |
| elementOffset | **int32_t**\& | スパンが重複している場合にオフセットを受け取る出力パラメータ |

### 戻り値

スパンが共通のメモリ位置を共有している場合は true、そうでない場合は false

## 関連項目

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)