---
title: ECCurve
second_title: Aspose.Slides برای C++ مرجع API
description: یک منحنی بیضوی.
type: docs
weight: 716
url: /fa/system.security.cryptography/eccurve/
---
## ECCurve struct

یک منحنی بیضوی.

```cpp
class ECCurve
```

## متدها

| Method | توضیح |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | یک منحنی را از نام دوستانه OID مشخص شده ایجاد می‌کند. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | یک منحنی را از oid مشخص شده ایجاد می‌کند. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | یک منحنی را از مقدار OID مشخص شده ایجاد می‌کند. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | [Oid](../oid/) نمایانگر منحنی نام‌گذاری‌شده را دریافت می‌کند. |
| void [Validate](./validate/)() const | منحنی فعلی را اعتبارسنجی می‌کند. |

## شمارنده‌ها

| شمارنده | توضیح |
| --- | --- |
| [ECCurveType](./eccurvetype/) | نوع منحنی بیضوی. |

## مراجع

* فضای‌نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)