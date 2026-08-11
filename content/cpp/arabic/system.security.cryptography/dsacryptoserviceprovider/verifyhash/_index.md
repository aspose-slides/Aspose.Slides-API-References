---
title: VerifyHash()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفحص توقيع البيانات.
type: docs
weight: 222
url: /ar/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) طريقة

يتحقق من توقيع البيانات.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التجزئة المحسوبة للبيانات المستلمة. |
| str | const [String](../../../system/string/)\& | اسم خوارزمية التجزئة المستخدمة. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التوقيع كما تم استلامه. |

### قيمة الإرجاع

صحيح إذا كان التوقيع صالحًا، خطأ وإلا.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [String](../../../system/string/)
* فئة [DSACryptoServiceProvider](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)