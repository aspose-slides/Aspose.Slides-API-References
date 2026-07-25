---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用スパンに指定された範囲外の要素が含まれているかどうかを確認します。
type: docs
weight: 79
url: /ja/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された範囲外の要素が読み取り専用スパンに含まれているかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型（比較可能である必要があります） |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 下限（包括） |
| highInclusive | const T\& | 上限（包括） |

### 戻り値

範囲外の要素が見つかった場合は true、それ以外の場合は false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 関数

指定された範囲外の要素が可変スパンに含まれているかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型（比較可能である必要があります） |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| lowInclusive | const T\& | 下限（包括） |
| highInclusive | const T\& | 上限（包括） |

### 戻り値

範囲外の要素が見つかった場合は true、それ以外の場合は false

## 参照

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)