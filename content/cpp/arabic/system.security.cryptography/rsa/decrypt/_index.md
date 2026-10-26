---
title: Decrypt()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بفك تشفير البيانات المدخلة باستخدام وضع الحشو المحدد.
type: docs
weight: 27
url: /ar/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) طريقة

يفك تشفير البيانات المدخلة باستخدام وضع الحشو المحدد.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) مصفوفة لفك التشفير. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | وضع الحشو. |

### قيمة الإرجاع

بيانات مفكوكة في تنسيق مصفوفة البايت.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [RSAEncryptionPadding](../../rsaencryptionpadding/)
* فئة [RSA](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)