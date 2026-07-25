---
title: AsSpan()
second_title: Aspose.Slides for C++ APIリファレンス
description: 配列からスパンを作成します。
type: docs
weight: 1
url: /ja/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) 関数

配列からスパンを作成します。

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列内の要素の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 元の配列です。 |
| start | **int32_t** | 配列内の開始インデックスです。 |
| length | **int32_t** | スパンの長さです。 |

### 戻り値

指定された配列の部分を表す Span<T>。

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) 関数

文字列から読み取り専用スパンを作成します。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | 元の文字列です。 |
| start | **int32_t** | 文字列内の開始インデックスです。 |
| length | **int32_t** | スパンの長さです。 |

### 戻り値

指定された文字列の部分を表す ReadOnlySpan<char16_t>。

## 参照

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)