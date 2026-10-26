---
title: VerifyHash()
second_title: مرجع API Aspose.Slides للـ C++
description: يتحقق من توقيع البيانات.
type: docs
weight: 118
url: /ar/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) طريقة


يتحقق من توقيع البيانات.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | الهاش المحسوب للبيانات المستلمة. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | التوقيع كما تم استلامه. |

### قيمة الإرجاع

صحيح إذا كان التوقيع صالحًا، وإلا خاطئ.

## راجع أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [ECDsa](../)
* مسافة اسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)