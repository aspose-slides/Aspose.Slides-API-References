---
title: VerifyHash()
second_title: مرجع API Aspose.Slides للـ C++
description: يتحقق من أن توقيع التجزئة المحددة صالح.
type: docs
weight: 170
url: /ar/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) طريقة

يتحقق من أن توقيع التجزئة المحددة صالح.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### المعاملات

| المعامل | نوع | الوصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | قيمة التجزئة للبيانات الموقعة. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | وضع الحشو. تُرجع true إذا كان التوقيع صالحًا، وإلا - false. |

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [RSASignaturePadding](../../rsasignaturepadding/)
* فئة [RSA](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)