---
title: Trim()
second_title: Aspose.Slides for C++ API リファレンス
description: 型付きスパンの両端から指定された要素を削除します。
type: docs
weight: 365
url: /ja/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) 関数

型付きスパンの両端から指定された要素を削除します。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムするスパン |
| trimElement | T | トリムする要素 |

### 戻り値

両端から指定された要素が削除された新しいスパン

## System::MemoryExtensions::Trim(Span\<T\>\&, T) 関数

可変型付きスパンの両端から指定された要素を削除します。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリムする可変スパン |
| trimElement | T | トリムする要素 |

### 戻り値

両端から指定された要素が削除された新しいスパン

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

型付きスパンの両端から指定された要素群を削除します。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムするスパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

両端から指定された要素群が削除された新しいスパン

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

可変型付きスパンの両端から指定された要素群を削除します。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリムする可変スパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

両端から指定された要素群が削除された新しいスパン

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) 関数

文字スパンの両端から空白文字を削除します。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字スパン |

### 戻り値

両端から空白が削除された新しいスパン

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) 関数

可変文字スパンの両端から空白文字を削除します。

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリムする可変文字スパン |

### 戻り値

両端から空白が削除された新しいスパン

## 関連項目

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)