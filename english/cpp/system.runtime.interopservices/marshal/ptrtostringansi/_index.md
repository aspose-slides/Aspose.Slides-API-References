---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API Reference
description: Creates a managed String from an unmanaged zero-terminated UTF8-string.
type: docs
weight: 235
url: /cpp/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) method


Creates a managed [String](../../../system/string/) from an unmanaged zero-terminated UTF8-string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | IntPtr | Pointer to the unmanaged string. |

### Return Value

A managed string.

## Marshal::PtrToStringAnsi(IntPtr, int) method


Creates a managed [String](../../../system/string/) from an unmanaged UTF8-string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | IntPtr | Pointer to the unmanaged string. |
| length | int | Length of the unmanaged string. |

### Return Value

A managed string.

## See Also

* Class [String](../../../system/string/)
* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)