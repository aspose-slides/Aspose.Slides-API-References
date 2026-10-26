---
title: PtrToStringUTF8()
second_title: Aspose.Slides for C++ API 參考文件
description: 從未受管理的零結尾 UTF8-string 建立受管理的 String。
type: docs
weight: 313
url: /zh-hant/system.runtime.interopservices/marshal/ptrtostringutf8/
---
## Marshal::PtrToStringUTF8(IntPtr) method

從未受管理的零結尾 UTF8 字串建立受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理字串的指標。 |

### 返回值

受管理的字串。

## Marshal::PtrToStringUTF8(IntPtr, int) method

從未受管理的 UTF8 字串建立受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr, int length)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理字串的指標。 |
| length | int | 未受管理字串的長度。 |

### 返回值

受管理的字串。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)