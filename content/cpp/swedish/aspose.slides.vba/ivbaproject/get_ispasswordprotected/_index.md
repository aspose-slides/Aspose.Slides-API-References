---
title: get_IsPasswordProtected()
second_title: Aspose.Slides för C++ API-referens
description: Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Skrivskyddad bool.
type: docs
weight: 40
url: /sv/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metod


Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Skrivskyddad **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Se även

* Klass [IVbaProject](../)
* Namnrymd [Aspose::Slides::Vba](../../)
* Bibliotek [Aspose.Slides](../../../)