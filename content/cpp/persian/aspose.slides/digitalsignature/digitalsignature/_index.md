---
title: DigitalSignature()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء DigitalSignature جدید را با گواهی مشخص‌شده ایجاد می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) سازنده

یک شیء [DigitalSignature](../) جدید را با گواهی مشخص‌شده ایجاد می‌کند.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | گواهی‌ای که برای امضای ارائه استفاده خواهد شد. |

## DigitalSignature::DigitalSignature(System::String, System::String) سازنده

یک شیء [DigitalSignature](../) جدید را با مسیر فایل گواهی مشخص‌شده و گذرواژه ایجاد می‌کند.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | مسیر به فایلی که حاوی گواهی است. |
| password | [System::String](../../../system/string/) | گذرواژه مورد نیاز برای دسترسی به گواهی. |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* کلاس [DigitalSignature](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)