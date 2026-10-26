---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides の C++ API リファレンス
description: スパン内で指定された範囲の任意の要素の最後の出現を検索します。
type: docs
weight: 261
url: /ja/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された範囲内の任意の要素の最後の出現位置を、スパン内で検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

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

範囲内の最後の要素のゼロベースインデックス、見つからない場合は -1 を返します。

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) 関数

指定された範囲内の任意の要素の最後の出現位置を、変更可能なスパン内で検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

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

範囲内の最後の要素のゼロベースインデックス、見つからない場合は -1 を返します。

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)