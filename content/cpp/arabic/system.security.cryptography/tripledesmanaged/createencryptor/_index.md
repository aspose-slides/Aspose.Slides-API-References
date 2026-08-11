---
title: CreateEncryptor()
second_title: Aspose.Slides لمرجع API C++
description: ينشئ كائن مشفر باستخدام معلمات صريحة.
type: docs
weight: 1
url: /ar/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن مشفر باستخدام معلمات صريحة.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مفتاح التشفير في شكل مصفوفة بايت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية في شكل مصفوفة بايت. |

### قيمة الإرجاع

كائن مشفر تم إنشاؤه حديثًا.

## TripleDESManaged::CreateEncryptor() طريقة

ينشئ كائن مشفر بمعلمات معرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن مشفر بمعلمات معرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [TripleDESManaged](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)