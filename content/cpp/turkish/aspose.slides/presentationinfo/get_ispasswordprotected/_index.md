---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API Referansı
description: Bağlı bir sunumun açmak için şifreyle korunup korunmadığını gösteren bir değer alır.
type: docs
weight: 14
url: /tr/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() yöntemi

Bağlı bir sunumun açmak için bir şifre ile korunup korunmadığını gösteren bir değer alır.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```
## Açıklamalar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```
## Ayrıca Bakınız

* Sınıf [PresentationInfo](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)