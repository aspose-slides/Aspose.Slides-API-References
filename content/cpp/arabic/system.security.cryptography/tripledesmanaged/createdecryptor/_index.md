---
title: CreateDecryptor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن فك التشفير باستخدام معلمات صريحة.
type: docs
weight: 14
url: /ar/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن فك التشفير باستخدام معلمات صريحة.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### معلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مفتاح التشفير في شكل مصفوفة بايت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية في شكل مصفوفة بايت. |

### قيمة الإرجاع

كائن فك التشفير الذي تم إنشاؤه حديثًا.

## TripleDESManaged::CreateDecryptor() طريقة

ينشئ كائن فك التشفير باستخدام المعلمات المحددة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن فك التشفير باستخدام المعلمات المحددة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [TripleDESManaged](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)