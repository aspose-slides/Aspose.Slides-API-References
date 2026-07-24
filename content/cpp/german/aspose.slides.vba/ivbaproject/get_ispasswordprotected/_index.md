---
title: get_IsPasswordProtected()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. Nur-Lesen bool.
type: docs
weight: 40
url: /de/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() Methode


Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. Nur-Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Siehe auch

* Klasse [IVbaProject](../)
* Namensraum [Aspose::Slides::Vba](../../)
* Bibliothek [Aspose.Slides](../../../)