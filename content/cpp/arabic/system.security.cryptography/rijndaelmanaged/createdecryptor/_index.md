---
title: CreateDecryptor()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ كائن مُفكّ تشفير مع معلمات صريحة.
type: docs
weight: 14
url: /ar/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن مُفكّ تشفير مع معلمات صريحة.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مفتاح التشفير في شكل مصفوفة بايت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية في شكل مصفوفة بايت. |

### قيمة الإرجاع

كائن مُفكّ تشفير تم إنشاؤه حديثًا.

## RijndaelManaged::CreateDecryptor() طريقة

ينشئ كائن مُفكّ تشفير مع المعلمات المعرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ كائن مُفكّ تشفير مع المعلمات المعرفة بواسطة كائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [RijndaelManaged](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)