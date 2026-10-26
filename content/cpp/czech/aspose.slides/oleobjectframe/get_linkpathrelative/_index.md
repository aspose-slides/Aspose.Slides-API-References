---
title: get_LinkPathRelative()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec. Jen pro čtení System::String."
type: docs
weight: 131
url: /cs/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() metoda

Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec. Jen pro čtení [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Poznámky

V prezentacích Ppt mohou některé odkazy Ole objektů mít relativní reprezentaci.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [OleObjectFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)