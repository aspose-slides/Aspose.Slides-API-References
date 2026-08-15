---
title: StartsWith()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查 span 是否以指定的值開頭。
type: docs
weight: 352
url: /zh-hant/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) 函式

檢查 span 是否以指定的值開頭。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查的 span |
| value | const T\& | 要在 span 開頭檢查的值 |

### 返回值

如果 span 以該值開頭則返回 true，否則返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查 span 是否以指定的值 span 開頭。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要在開頭檢查的值的 span |

### 返回值

如果 span 以該值 span 開頭則返回 true，否則返回 false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查可變 span 是否以指定的唯讀值 span 開頭。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要檢查的可變 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要檢查的值的唯讀 span |

### 返回值

如果 span 以該值 span 開頭則返回 true，否則返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 函式

檢查唯讀 span 是否以指定的可變值 span 開頭。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查的唯讀 span |
| value | const [Span](../../system/span/)\<T\>\& | 包含要檢查的值的可變 span |

### 返回值

如果 span 以該值 span 開頭則返回 true，否則返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式

使用字串比較檢查字符 span 是否以指定的值 span 開頭。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要檢查的字符 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 包含要檢查的值的字符 span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要執行的字串比較類型 |

### 返回值

如果 span 以該值 span 開頭則返回 true，否則返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) 函式

檢查字串 span 是否以指定的字符陣列開頭。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | 要檢查的字串 span |
| val | const char16_t * | 要在開頭檢查的字符陣列 |

### 返回值

如果 span 以該字符陣列開頭則返回 true，否則返回 false

## 另請參見

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)