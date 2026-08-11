---
title: VerifyHash()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق من توقيع البيانات.
type: docs
weight: 183
url: /ar/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) طريقة

يتحقق من توقيع البيانات.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | الهاش المحسوب للبيانات المستلمة. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | التوقيع المستلم. |

### قيمة الإرجاع

True إذا كان التوقيع صالحًا، false خلاف ذلك.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [ECDsaBotan](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)