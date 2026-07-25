---
title: SequenceEqual()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 2つの ReadOnlySpans が同じ順序で同一の要素を含むかどうかを判定します。
type: docs
weight: 326
url: /ja/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


2つの ReadOnlySpans が同じ順序で同一の要素を含むかどうかを判定します。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### 戻り値

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


[Span](../../system/span/) と [ReadOnlySpan](../../system/readonlyspan/) が同じ順序で同一の要素を含むかどうかを判定します。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### 戻り値

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 関数


カスタム比較子を使用して、2つの ReadOnlySpans が等しい要素を含むかどうかを判定します。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### 戻り値

true if spans have same length and comparer considers all elements equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 関数


[Span](../../system/span/) と [ReadOnlySpan](../../system/readonlyspan/) がカスタム比較子を使用して等しい要素を含むかどうかを判定します。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### 戻り値

true if spans have same length and comparer considers all elements equal, false otherwise

## 参照

* Typedef [SharedPtr](../../system/sharedptr/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)