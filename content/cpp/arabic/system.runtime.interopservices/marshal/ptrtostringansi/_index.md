---
title: PtrToStringAnsi()
second_title: مرجع API Aspose.Slides للغة C++
description: إنشاء سلسلة String مُدارة من سلسلة UTF8 غير مُدارة منتهية بصفر.
type: docs
weight: 274
url: /ar/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) طريقة

Creates a managed [String](../../../system/string/) from an unmanaged zero-terminated UTF8-string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | IntPtr | مؤشر إلى السلسلة غير المُدارة. |

### قيمة الإرجاع

سلسلة مُدارة.

## Marshal::PtrToStringAnsi(IntPtr, int) طريقة

Creates a managed [String](../../../system/string/) from an unmanaged UTF8-string.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | IntPtr | مؤشر إلى السلسلة غير المُدارة. |
| length | int | طول السلسلة غير المُدارة. |

### قيمة الإرجاع

سلسلة مُدارة.

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [Marshal](../)
* نطاق [System::Runtime::InteropServices](../../)
* مكتبة [Aspose.Slides](../../../)