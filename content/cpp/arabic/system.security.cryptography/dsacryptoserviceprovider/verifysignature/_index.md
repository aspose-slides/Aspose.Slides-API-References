---
title: VerifySignature()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: تحقق من توقيع DSA للبيانات المحددة.
type: docs
weight: 118
url: /ar/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) طريقة

تحقق من توقيع [DSA](../../dsa/) للبيانات المحددة.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) موقَّعة بـ **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) توقيع. |

### قيمة الإرجاع

true - إذا كان **rgb_signature** يطابق توقيع [DSA](../../dsa/) المحسوب على **rgb_hash**، وإلا - false.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [DSACryptoServiceProvider](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)