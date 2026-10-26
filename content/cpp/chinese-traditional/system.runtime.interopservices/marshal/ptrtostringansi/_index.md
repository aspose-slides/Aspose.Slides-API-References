---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API 參考
description: 從未託管的零結尾 UTF8 字串建立受管理的 String。
type: docs
weight: 274
url: /zh-hant/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) 方法

從未託管的以零結尾的 UTF8 字串建立受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未託管字串的指標。 |

### 返回值

受管理的字串。

## Marshal::PtrToStringAnsi(IntPtr, int) 方法

從未託管的 UTF8 字串建立受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未託管字串的指標。 |
| length | int | 未託管字串的長度。 |

### 返回值

受管理的字串。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)