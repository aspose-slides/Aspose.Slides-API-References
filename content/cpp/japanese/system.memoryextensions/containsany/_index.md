---
title: ContainsAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用スパンが 2 つの値のいずれかを含んでいるかを確認します。
type: docs
weight: 53
url: /ja/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

読み取り専用スパンが 2 つの値のいずれかを含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |

### 戻り値

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

読み取り専用スパンが 3 つの値のいずれかを含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |
| value2 | const T\& | 検索する 3 番目の値 |

### 戻り値

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function

可変スパンが 2 つの値のいずれかを含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |

### 戻り値

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

可変スパンが 3 つの値のいずれかを含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| value0 | const T\& | 検索する最初の値 |
| value1 | const T\& | 検索する 2 番目の値 |
| value2 | const T\& | 検索する 3 番目の値 |

### 戻り値

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

読み取り専用スパンが別のスパンから任意の値を含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する値のスパン |

### 戻り値

true if any value from values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

可変スパンが読み取り専用スパンから任意の値を含んでいるかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索する読み取り専用スパンの値 |

### 戻り値

true if any value from values is found in span, false otherwise

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)