---
title: SignHash()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب التوقيع للقيمة التجزئة المحددة.
type: docs
weight: 196
url: /ar/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) طريقة

يحسب التوقيع لقيمة التجزئة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | قيمة التجزئة. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | خوارزمية التجزئة. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | وضع الحشو. إرجاع [RSA](../../rsa/) التوقيع للقيمة التجزئة المحددة. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) طريقة

يحسب التوقيع للقيمة المدخلة المحددة. غير مُنفّذ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | قيمة التجزئة للبيانات التي يجب توقيعها. |
| str | const [String](../../../system/string/)\& | معرف خوارزمية التجزئة المستخدم لإنشاء التجزئة. |

### قيمة الإرجاع

[RSA](../../rsa/) التوقيع للبيانات المحددة.

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)