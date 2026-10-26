---
title: Encrypt()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتشفير الرسالة. غير مُنفّذ.
type: docs
weight: 118
url: /ar/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) طريقة

يقوم بتشفير الرسالة. غير مُنفّذ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) لتشفير. |
| use_oaep | **bool** | صحيح لاستخدام حشو OAEP، خطأ لاستخدام حشو PKCS#1 v1.5. |

### قيمة الإرجاع

مصفوفة البيانات المشفّرة.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) طريقة

يقوم بتشفير البيانات المدخلة باستخدام وضع الحشو المحدد.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) مصفوفة للتشفير. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | وضع الحشو. |

### قيمة الإرجاع

البيانات المشفّرة بصيغة مصفوفة بايت.

## راجع أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [RSACryptoServiceProvider](../)
* فئة [RSAEncryptionPadding](../../rsaencryptionpadding/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)