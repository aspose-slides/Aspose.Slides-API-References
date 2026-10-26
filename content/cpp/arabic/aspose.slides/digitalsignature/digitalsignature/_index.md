---
title: DigitalSignature()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن DigitalSignature جديد باستخدام الشهادة المحددة.
type: docs
weight: 66
url: /ar/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) منشئ


ينشئ كائنًا جديدًا من [DigitalSignature](../) باستخدام الشهادة المحددة.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | الشهادة التي ستُستخدم لتوقيع العرض التقديمي. |

## DigitalSignature::DigitalSignature(System::String, System::String) منشئ


ينشئ كائنًا جديدًا من [DigitalSignature](../) باستخدام مسار ملف الشهادة وكلمة المرور المحددة.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | المسار إلى ملف الشهادة. |
| password | [System::String](../../../system/string/) | كلمة المرور المطلوبة للوصول إلى الشهادة. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* فئة [DigitalSignature](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)