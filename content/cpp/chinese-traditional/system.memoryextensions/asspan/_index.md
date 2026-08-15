---
title: AsSpan()
second_title: Aspose.Slides for C++ API 參考文件
description: 從陣列建立 span。
type: docs
weight: 1
url: /zh-hant/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) function

建立從陣列產生的 span。

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 陣列中元素的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 來源陣列。 |
| start | **int32_t** | 陣列的起始索引。 |
| length | **int32_t** | span 的長度。 |

### 返回值

Span<T>，跨越陣列指定的部分。

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) function

建立從字串產生的唯讀 span。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | 來源字串。 |
| start | **int32_t** | 字串的起始索引。 |
| length | **int32_t** | span 的長度。 |

### 返回值

ReadOnlySpan<char16_t>，跨越字串指定的部分。

## 另見

* 型別定義 [ArrayPtr](../../system/arrayptr/)
* 類別 [Span](../../system/span/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [String](../../system/string/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)