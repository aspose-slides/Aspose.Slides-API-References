---
title: Encrypt()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتشفير البيانات المدخلة باستخدام وضع الحشو المحدد.
type: docs
weight: 53
url: /ar/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) طريقة

يقوم بتشفير البيانات المدخلة باستخدام وضع الحشو المحدد.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array to encrypt. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding mode. |

### قيمة الإرجاع

البيانات المشفرة بصيغة مصفوفة بايت.

## انظر أيضًا

* تعريف النوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [RSAEncryptionPadding](../../rsaencryptionpadding/)
* فئة [RSA](../)
* نطاق الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)