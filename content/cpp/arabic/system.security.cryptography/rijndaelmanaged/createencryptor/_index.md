---
title: CreateEncryptor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن المشفر بمعلمات صريحة.
type: docs
weight: 1
url: /ar/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن المشفر بمعلمات صريحة.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مفتاح التشفير في شكل مصفوفة بايت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية في شكل مصفوفة بايت. |

### قيمة الإرجاع

كائن المشفر الذي تم إنشاؤه حديثًا.

## RijndaelManaged::CreateEncryptor() طريقة

ينشئ كائن المشفر بالمعلمات المحددة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن المشفر بالمعلمات المحددة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [RijndaelManaged](../)
* مساحة اسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)