---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API Referansı
description: Bağlı bir sunumun yazma korumalı olup olmadığını gösteren bir değer alır.
type: docs
weight: 27
url: /tr/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() method

Bağlı bir sunumun yazma korumalı olup olmadığını gösteren bir değer alır.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Açıklamalar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

Sunum açmak için bir parola ile korunduysa, özellik değeri NotDefined olur. Bkz. [NullableBool](../../nullablebool/) sayımı.

## İlgili

* Enum [NullableBool](../../nullablebool/)
* Sınıf [IPresentationInfo](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)