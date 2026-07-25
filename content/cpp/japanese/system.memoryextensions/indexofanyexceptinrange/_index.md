---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API リファレンス
description: ReadOnlySpan<T> において、指定された範囲外にある最初の要素のインデックスを取得します
type: docs
weight: 183
url: /ja/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された範囲外にある最初の要素のインデックスを ReadOnlySpan<T> で検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 範囲の下限（包含） |
| highInclusive | const T\& | 範囲の上限（包含） |

### 戻り値

範囲外の最初の要素の0ベースインデックス、または見つからない場合は -1

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 関数

指定された範囲外にある最初の要素のインデックスを Span<T> で検索します

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 範囲の下限（包含） |
| highInclusive | const T\& | 範囲の上限（包含） |

### 戻り値

範囲外の最初の要素の0ベースインデックス、または見つからない場合は -1

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)