---
title: get_LinkPathRelative()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací relativní cestu k propojenému souboru, pokud je přítomna, jinak vrací prázdný řetězec. Pouze pro čtení System::String."
type: docs
weight: 118
url: /cs/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() metoda


Vrací relativní cestu k propojenému souboru, pokud je přítomna, jinak vrací prázdný řetězec. Pouze pro čtení [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Poznámky


V prezentacích Ppt mohou některé odkazy na Ole objekty mít relativní reprezentaci. 


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
* Třída [IOleObjectFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)