---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides の C++ API リファレンス
description: スパン内で、指定された範囲外の任意の要素の最後の出現を検索します。
type: docs
weight: 248
url: /ja/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された範囲の外にある任意の要素の最後の出現位置を、スパン内で検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 戻り値

範囲外の最後の要素のゼロ基準インデックス、見つからなければ -1 を返します

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 関数

指定された範囲の外にある任意の要素の最後の出現位置を、可変スパン内で検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 戻り値

範囲外の最後の要素のゼロ基準インデックス、見つからなければ -1 を返します

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)