---
title: Decrypt()
second_title: مرجع API Aspose.Slides للغة C++
description: يفك تشفير الرسالة. غير مُنفّذ.
type: docs
weight: 105
url: /ar/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method

يفك تشفير الرسالة. غير مُنفَّذ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) لفك التشفير. |
| use_oaep | **bool** | صحيح لاستخدام تعبئة OAEP، خطأ لاستخدام تعبئة PKCS#1 v1.5. |

### قيمة الإرجاع

مصفوفة البيانات المفكوكة.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

يفك تشفير بيانات الإدخال باستخدام وضع التعبئة المحدد.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | مصفوفة [Byte](../../../system/byte/) لفك التشفير. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | وضع التعبئة. |

### قيمة الإرجاع

البيانات المفكوكة بصيغة مصفوفة بايت.

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الصف [RSACryptoServiceProvider](../)
* الصف [RSAEncryptionPadding](../../rsaencryptionpadding/)
* مساحة الاسم [System::Security::Cryptography](../../)
* المكتبة [Aspose.Slides](../../../)