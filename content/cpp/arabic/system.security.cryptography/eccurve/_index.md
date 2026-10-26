---
title: ECCurve
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منحنى إهليلجي.
type: docs
weight: 716
url: /ar/system.security.cryptography/eccurve/
---
## ECCurve هيكل

منحنى إهليلجي.

```cpp
class ECCurve
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | إنشاء منحنى من الاسم الصديق المحدد لـ OID. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | إنشاء منحنى من الـ oid المحدد. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | إنشاء منحنى من قيمة OID المحددة. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | يحصل على [Oid](../oid/) التي تمثل المنحنى المسمى. |
| void [Validate](./validate/)() const | تحقق من صحة المنحنى الحالي. |
## التعدادات

| التعداد | الوصف |
| --- | --- |
| [ECCurveType](./eccurvetype/) | نوع المنحنى الإهليلجي. |
## انظر أيضًا

* النطاق [System::Security::Cryptography](../)
* المكتبة [Aspose.Slides](../../)