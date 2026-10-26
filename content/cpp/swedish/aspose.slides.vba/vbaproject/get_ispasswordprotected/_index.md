---
title: get_IsPasswordProtected()
second_title: Aspose.Slides för C++ API-referens
description: Indikerar huruvida VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Skrivskyddad bool.
type: docs
weight: 40
url: /sv/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metod


Indikerar huruvida VBAProject är skyddad med ett lösenord för att visa projektets egenskaper. Skrivskyddad **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Se också

* Klass [VbaProject](../)
* Namnrymd [Aspose::Slides::Vba](../../)
* Bibliotek [Aspose.Slides](../../../)