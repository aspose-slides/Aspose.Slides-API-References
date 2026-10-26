---
title: get_IsWriteProtected()
second_title: Aspose.Slides için C++ API Referansı
description: Bağlı bir sunumun yazma korumalı olup olmadığını gösteren bir değer alır.
type: docs
weight: 27
url: /tr/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() yöntemi

Bağlı bir sunumun yazma korumalı olup olmadığını gösteren bir değer alır.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Açıklamalar

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

Sunum açmak için bir parola ile korunuyorsa, özellik değeri NotDefined olur.

## Ayrıca Bakınız

* Enum [NullableBool](../../nullablebool/)
* Sınıf [PresentationInfo](../)
* İsimAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)