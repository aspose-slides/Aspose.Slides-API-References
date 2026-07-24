---
title: get_LinkPathRelative()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird eine leere Zeichenkette zurückgegeben. Nur lesend System::String."
type: docs
weight: 131
url: /de/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() Methode


Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird eine leere Zeichenkette zurückgegeben. Nur lesend [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Hinweise


In den Ppt-Präsentationen können einige Ole-Objektverknüpfungen eine relative Darstellung haben. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [OleObjectFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)