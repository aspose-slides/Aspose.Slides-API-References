---
title: CreateDecryptor()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ كائن فك التشفير بمعلمات صريحة.
type: docs
weight: 14
url: /ar/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن فك التشفير بمعلمات صريحة.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مفتاح التشفير في شكل مصفوفة بايت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية في شكل مصفوفة بايت. |

### قيمة الإرجاع

كائن فك التشفير الذي تم إنشاؤه حديثًا.

## RC2Managed::CreateDecryptor() طريقة

ينشئ كائن فك التشفير بمعلمات معرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن فك التشفير بمعلمات معرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [RC2Managed](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)