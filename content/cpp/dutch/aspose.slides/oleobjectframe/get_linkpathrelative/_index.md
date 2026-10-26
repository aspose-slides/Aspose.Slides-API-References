---
title: get_LinkPathRelative()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders retourneert een lege tekenreeks. Alleen-lezen System::String."
type: docs
weight: 131
url: /nl/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() methode


Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders retourneert een lege string. Alleen-lezen [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Opmerkingen


In de Ppt-presentaties kunnen sommige Ole-objectkoppelingen een relatieve weergave hebben. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [OleObjectFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)