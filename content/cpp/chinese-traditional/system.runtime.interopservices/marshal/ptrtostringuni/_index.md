---
title: PtrToStringUni()
second_title: Aspose.Slides for C++ API 參考文件
description: 從未受管理的零結束 Unicode 字串建立受管理的 String。
type: docs
weight: 300
url: /zh-hant/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) method


建立受管理的 [String](../../../system/string/)，來源為未受管理的零結束 Unicode 字串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理字串的指標。 |

### 回傳值

受管理的 string。

## Marshal::PtrToStringUni(IntPtr, int) method


建立受管理的 [String](../../../system/string/)，來源為未受管理的 Unicode 字串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理字串的指標。 |
| length | int | 未受管理字串的長度。 |

### 回傳值

受管理的 string。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)