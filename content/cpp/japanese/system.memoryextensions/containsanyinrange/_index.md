---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された範囲内に要素が含まれているかどうかを、読み取り専用スパンでチェックします。
type: docs
weight: 92
url: /ja/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

指定された範囲内に要素が含まれているかどうかを、読み取り専用スパンでチェックします。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型（比較可能である必要があります） |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| lowInclusive | const T\& | 下限（包括） |
| highInclusive | const T\& | 上限（包括） |

### 戻り値

範囲内に要素が見つかった場合は true、見つからなかった場合は false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) 関数

指定された範囲内に要素が含まれているかどうかを、可変スパンでチェックします。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型（比較可能である必要があります） |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| lowInclusive | const T\& | 下限（包括） |
| highInclusive | const T\& | 上限（包括） |

### 戻り値

範囲内に要素が見つかった場合は true、見つからなかった場合は false

## 参照

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)