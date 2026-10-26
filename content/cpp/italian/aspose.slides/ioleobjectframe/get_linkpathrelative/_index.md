---
title: get_LinkPathRelative()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il percorso relativo a un file collegato se presente, altrimenti restituisce una stringa vuota. Solo lettura System::String."
type: docs
weight: 118
url: /it/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() metodo

Restituisce il percorso relativo a un file collegato se presente, altrimenti restituisce una stringa vuota. Solo lettura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Osservazioni

Nelle presentazioni Ppt, alcuni collegamenti di oggetti Ole possono avere una rappresentazione relativa.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IOleObjectFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)