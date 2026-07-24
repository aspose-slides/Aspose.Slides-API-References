---
title: get_LinkPathRelative()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird eine leere Zeichenfolge zurückgegeben. Nur lesbar System::String."
type: docs
weight: 118
url: /de/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() Methode

Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Anmerkungen

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
* Klasse [IOleObjectFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)