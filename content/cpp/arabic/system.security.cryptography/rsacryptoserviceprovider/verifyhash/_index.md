---
title: VerifyHash()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفحص توقيع البيانات.
type: docs
weight: 222
url: /ar/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) طريقة

يفحص توقيع البيانات.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التجزئة المحسوبة للبيانات المستلمة. |
| str | const [String](../../../system/string/)\& | اسم خوارزمية التجزئة المستخدمة. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التوقيع المستلم. |

### قيمة الإرجاع

صحيح إذا كان التوقيع صالحًا، وإلا خاطئ.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) طريقة

يتحقق من أن توقيع التجزئة المحددة صالح.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | قيمة التجزئة للبيانات الموقعة. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | وضع الحشو. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [RSACryptoServiceProvider](../)
* فئة [RSASignaturePadding](../../rsasignaturepadding/)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* نطاق أسماء [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)