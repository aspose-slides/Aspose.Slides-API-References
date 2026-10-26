---
title: TrimStart()
second_title: Aspose.Slides for C++ API リファレンス
description: 型付きスパンの先頭から指定された要素をトリムします。
type: docs
weight: 391
url: /ja/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) 関数

指定された要素を型付きスパンの先頭からトリムします。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリム対象のスパン |
| trimElement | const T\& | トリムする要素 |

### 戻り値

先頭から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) 関数

指定された要素を可変型付きスパンの先頭からトリムします。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリム対象の可変スパン |
| trimElement | const T\& | トリムする要素 |

### 戻り値

先頭から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

指定された要素群を型付きスパンの先頭からトリムします。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリム対象のスパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

先頭から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

指定された要素群を可変型付きスパンの先頭からトリムします。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリム対象の可変スパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

先頭から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) 関数

文字スパンの先頭から空白文字をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリム対象の文字スパン |

### 戻り値

先頭から空白文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) 関数

可変文字スパンの先頭から空白文字をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリム対象の可変文字スパン |

### 戻り値

先頭から空白文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) 関数

文字スパンの先頭から指定された文字をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリム対象の文字スパン |
| trimchar | char16_t | トリムする文字 |

### 戻り値

先頭から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) 関数

可変文字スパンの先頭から指定された文字をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリム対象の可変文字スパン |
| trimchar | char16_t | トリムする文字 |

### 戻り値

先頭から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 関数

文字スパンの先頭から指定された文字群をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリム対象の文字スパン |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字群 |

### 戻り値

先頭から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 関数

可変文字スパンの先頭から指定された文字群をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリム対象の可変文字スパン |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字群 |

### 戻り値

先頭から指定された文字がトリムされた新しいスパン

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)