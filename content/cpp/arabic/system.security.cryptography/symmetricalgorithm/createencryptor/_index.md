---
title: CreateEncryptor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مشفرًا باستخدام المعلمات المرتبطة بكائن الخوارزمية.
type: docs
weight: 183
url: /ar/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() طريقة

ينشئ مشفرًا باستخدام المعلمات المرتبطة بكائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### قيمة الإرجاع

كائن المشفر المُنشأ حديثًا.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ مشفرًا باستخدام معلمات صريحة.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المفتاح للاستخدام. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية للاستخدام. |

### قيمة الإرجاع

كائن المشفر المُنشأ حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* صنف [ICryptoTransform](../../icryptotransform/)
* صنف [SymmetricAlgorithm](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)