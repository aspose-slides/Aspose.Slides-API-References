---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 2 つの ReadOnlySpan を辞書順に比較します。
type: docs
weight: 313
url: /ja/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

2つの ReadOnlySpan を辞書順に比較します。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 比較する最初の span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 比較する 2 番目の span |

### 戻り値

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

辞書順に [Span](../../system/span/) と [ReadOnlySpan](../../system/readonlyspan/) を比較します。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 比較する [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 比較する [ReadOnlySpan](../../system/readonlyspan/) |

### 戻り値

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

辞書順に [ReadOnlySpan](../../system/readonlyspan/) と [Span](../../system/span/) を比較します。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 比較する [ReadOnlySpan](../../system/readonlyspan/) |
| other | const [Span](../../system/span/)\<T\>\& | 比較する [Span](../../system/span/) |

### 戻り値

- 1 if span < other, 0 if span == other, 1 if span > other

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)