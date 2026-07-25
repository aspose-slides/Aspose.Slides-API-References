---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された範囲内にある最初の要素のインデックスを ReadOnlySpan<T> から検索します
type: docs
weight: 196
url: /ja/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ReadOnlySpan<T> 内で、指定された範囲に含まれる最初の要素のインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 範囲の下限（含む） |
| highInclusive | const T\& | 範囲の上限（含む） |

### 戻り値

範囲内にある最初の要素の 0 基準インデックス、見つからない場合は -1 が返されます

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Span<T> 内で、指定された範囲に含まれる最初の要素のインデックスを検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 範囲の下限（含む） |
| highInclusive | const T\& | 範囲の上限（含む） |

### 戻り値

範囲内にある最初の要素の 0 基準インデックス、見つからない場合は -1 が返されます

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)