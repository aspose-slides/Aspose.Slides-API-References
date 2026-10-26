---
title: StartsWith()
second_title: Aspose.Slides for C++ API リファレンス
description: スパンが指定された値で始まるかどうかを確認します。
type: docs
weight: 352
url: /ja/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) 関数

スパンが指定された値で始まるかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 確認するスパン |
| value | const T\& | スパンの先頭で確認する値 |

### 戻り値

スパンがその値で始まる場合は true、そうでない場合は false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

スパンが指定された値スパンで始まるかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 確認するスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 先頭で確認する値を含むスパン |

### 戻り値

スパンがその値スパンで始まる場合は true、そうでない場合は false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

変更可能なスパンが指定された読み取り専用の値スパンで始まるかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 確認する変更可能なスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 確認する値を含む読み取り専用スパン |

### 戻り値

スパンがその値スパンで始まる場合は true、そうでない場合は false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 関数

読み取り専用スパンが指定された変更可能な値スパンで始まるかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 確認する読み取り専用スパン |
| value | const [Span](../../system/span/)\<T\>\& | 確認する値を含む変更可能スパン |

### 戻り値

スパンがその値スパンで始まる場合は true、そうでない場合は false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数

文字スパンが文字列比較を使用して指定された値スパンで始まるかどうかを確認します。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 確認する文字スパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 確認する値を含む文字スパン |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 実行する文字列比較の種類 |

### 戻り値

スパンがその値スパンで始まる場合は true、そうでない場合は false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) 関数

文字列スパンが指定された文字配列で始まるかどうかを確認します。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | 確認する文字列スパン |
| val | const char16_t * | 先頭で確認する文字配列 |

### 戻り値

スパンがその文字配列で始まる場合は true、そうでない場合は false

## 参照

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)