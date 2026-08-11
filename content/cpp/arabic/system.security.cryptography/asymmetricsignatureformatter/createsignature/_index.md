---
title: CreateSignature()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ التوقيع للبيانات المحددة.
type: docs
weight: 1
url: /ar/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) طريقة

يُنشئ التوقيع للبيانات المحددة.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) لحساب التجزئة لـ. |

### قيمة الإرجاع

التوقيع المحسوب على شكل مصفوفة بايت.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) طريقة

يُنشئ التوقيع لقيمة التجزئة المحددة.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | خوارزمية التجزئة المستخدمة عند إنشاء التوقيع. |

### قيمة الإرجاع

التوقيع المحسوب على شكل مصفوفة بايت.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [AsymmetricSignatureFormatter](../)
* فئة [HashAlgorithm](../../hashalgorithm/)
* مساحة اسم [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)