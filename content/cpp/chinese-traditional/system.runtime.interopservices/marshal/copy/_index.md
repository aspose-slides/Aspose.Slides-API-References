---
title: Copy()
second_title: Aspose.Slides for C++ API 參考
description: 實作 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 語意。
type: docs
weight: 1
url: /zh-hant/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) 方法

實作 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 語意。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| container | 目標容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const IntPtr | 來源資料指標。 |
| destination | container\&& | 要將資料複製到的容器。 |
| startIndex | int | 來源起始索引。 |
| length | int | 要複製的元素數量。 |

## Marshal::Copy(const void *, container\&&, int, int) 方法

實作 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 語意。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| container | 目標容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const void * | 來源資料指標。 |
| destination | container\&& | 要將資料複製到的容器。 |
| startIndex | int | 來源起始索引。 |
| length | int | 要複製的元素數量。 |

## Marshal::Copy(const container\&, int, void *, int) 方法

實作 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| container | 來源容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const container\& | 來源資料指標。 |
| startIndex | int | 來源起始索引。 |
| destination | void * | 目標資料指標。 |
| length | int | 要複製的元素數量。 |

## Marshal::Copy(const container\&, int, IntPtr, int) 方法

實作 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| container | 來源容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const container\& | 來源資料指標。 |
| startIndex | int | 來源起始索引。 |
| destination | IntPtr | 目標資料指標。 |
| length | int | 要複製的元素數量。 |

## 相關參考

* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)