---
title: SignHash()
second_title: Aspose.Slides لمرجع API C++
description: يحسب التوقيع للقيمة التجزئة المحددة.
type: docs
weight: 144
url: /ar/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) طريقة

يحسب التوقيع للقيمة التجزئة المحددة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | قيمة التجزئة. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | خوارزمية التجزئة. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | وضع الحشو. إرجاع [RSA](../) توقيع للقيمة التجزئة المحددة. |

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [RSASignaturePadding](../../rsasignaturepadding/)
* فئة [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)