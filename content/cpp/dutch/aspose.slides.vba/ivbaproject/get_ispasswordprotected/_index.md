---
title: get_IsPasswordProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan of de VBAProject wordt beschermd door een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen bool.
type: docs
weight: 40
url: /nl/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() methode


Geeft aan of de VBAProject wordt beschermd door een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Klasse [IVbaProject](../)
* Naamruimte [Aspose::Slides::Vba](../../)
* Bibliotheek [Aspose.Slides](../../../)