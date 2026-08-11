---
title: CreateDecryptor()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مُفكّ تشفير مع المعلمات المرتبطة بكائن الخوارزمية.
type: docs
weight: 196
url: /ar/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() طريقة

ينشئ مُفكّ تشفير مع المعلمات المرتبطة بكائن الخوارزمية.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### قيمة الإرجاع

كائن مُفكّ تشفير تم إنشاؤه حديثًا.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

ينشئ مُفكّ تشفير مع معلمات صريحة.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المفتاح للاستخدام. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | القيمة الأولية للاستخدام. |

### قيمة الإرجاع

كائن مُفكّ تشفير تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../../icryptotransform/)
* فئة [SymmetricAlgorithm](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* المكتبة [Aspose.Slides](../../../)