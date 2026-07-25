---
title: TrimEnd()
second_title: Aspose.Slides for C++ API リファレンス
description: 型付きスパンの末尾から指定された要素をトリムします。
type: docs
weight: 378
url: /ja/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

型付きスパンの末尾から指定された要素をトリムします。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムするスパン |
| trimElement | const T\& | トリムする要素 |

### 戻り値

末尾から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

可変型付きスパンの末尾から指定された要素をトリムします。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリムする可変スパン |
| trimElement | const T\& | トリムする要素 |

### 戻り値

末尾から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

型付きスパンの末尾から指定された要素群をトリムします。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムするスパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

末尾から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

可変型付きスパンの末尾から指定された要素群をトリムします。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | トリムする可変スパン |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | トリムする要素群 |

### 戻り値

末尾から指定された要素がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

文字スパンの末尾から空白文字をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字スパン |

### 戻り値

末尾から空白がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

可変文字スパンの末尾から空白文字をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリムする可変文字スパン |

### 戻り値

末尾から空白がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

文字スパンの末尾から指定された文字をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字スパン |
| trimchar | char16_t | トリムする文字 |

### 戻り値

末尾から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

可変文字スパンの末尾から指定された文字をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリムする可変文字スパン |
| trimchar | char16_t | トリムする文字 |

### 戻り値

末尾から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

文字スパンの末尾から指定された文字群をトリムします。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字スパン |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字群 |

### 戻り値

末尾から指定された文字がトリムされた新しいスパン

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

可変文字スパンの末尾から指定された文字群をトリムします。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | トリムする可変文字スパン |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | トリムする文字群 |

### 戻り値

末尾から指定された文字がトリムされた新しいスパン

## 関連項目

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)