---
title: PtrToStringAuto()
second_title: Aspose.Slides for C++ API 參考
description: 從未受管理的零結尾字串建立受管理的 String。
type: docs
weight: 287
url: /zh-hant/system.runtime.interopservices/marshal/ptrtostringauto/
---
## Marshal::PtrToStringAuto(IntPtr) 方法

Creates a managed [String](../../../system/string/) from an unmanaged zero-terminated string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理的字串。 |

### 返回值

受管理的字串。

## Marshal::PtrToStringAuto(IntPtr, int) 方法

Creates a managed [String](../../../system/string/) from an unmanaged string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr, int length)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理的字串。 |
| length | int | 未受管理的字串長度。 |

### 返回值

受管理的字串。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)