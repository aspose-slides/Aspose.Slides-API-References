---
title: get_IsPasswordProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan of de VBAProject wordt beschermd met een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen bool.
type: docs
weight: 40
url: /nl/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() methode


Geeft aan of de VBAProject wordt beschermd met een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Zie ook

* Klasse [VbaProject](../)
* Naamruimte [Aspose::Slides::Vba](../../)
* Bibliotheek [Aspose.Slides](../../../)