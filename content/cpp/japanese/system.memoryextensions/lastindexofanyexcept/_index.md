---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API リファレンス
description: スパン内で、指定された3つの値を除く任意の要素の最後の出現を検索します。
type: docs
weight: 235
url: /ja/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

スパン内で、指定された3つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

可変スパン内で、指定された3つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

スパン内で、指定された2つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

可変スパン内で、指定された2つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

スパン内で、指定された1つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

可変スパン内で、指定された1つの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

スパン内で、シーケンスからの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

可変スパン内で、シーケンスからの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

可変スパン内で、可変シーケンスからの値を除く任意の要素の最後の出現を検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to exclude |

### 戻り値

The zero-based index of the last non-excluded element, or -1 if not found

## 参考

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)