---
title: get_IsPasswordProtected()
second_title: Aspose.Slides için C++ API Referansı
description: Bağlı bir sunumun açmak için bir parola ile korunup korunmadığını gösteren bir değer döndürür.
type: docs
weight: 14
url: /tr/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() yöntemi


Bağlanmış bir sunumun açmak için parola ile korunup korunmadığını gösteren bir değer döndürür.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Açıklamalar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Diğer Bağlantılar

* Sınıf [IPresentationInfo](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)