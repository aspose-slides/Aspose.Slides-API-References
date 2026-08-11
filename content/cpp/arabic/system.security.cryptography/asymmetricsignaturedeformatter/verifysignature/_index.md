---
title: VerifySignature()
second_title: مرجع API Aspose.Slides للـ C++
description: يتحقق من التوقيع على البيانات.
type: docs
weight: 27
url: /ar/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

يتحقق من التوقيع على البيانات.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) موقع باستخدام **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | التوقيع الذي سيُتحقق منه للبيانات. |

### قيمة الإرجاع

صحيح إذا نجح فحص التوقيع، خطأ وإلا.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) طريقة

يتحقق من التوقيع على البيانات. غير مُنفَّذ.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | الخوارزمية المستخدمة للتجزئة. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | التوقيع الذي سيُتحقق منه للبيانات. |

### قيمة الإرجاع

صحيح إذا نجح فحص التوقيع، خطأ وإلا.

## انظر أيضا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [AsymmetricSignatureDeformatter](../)
* فئة [HashAlgorithm](../../hashalgorithm/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)