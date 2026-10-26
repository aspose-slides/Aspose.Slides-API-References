---
title: get_LinkPathRelative()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. Endast läsning System::String."
type: docs
weight: 131
url: /sv/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() metod


Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. Endast läsning [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Anmärkningar


I Ppt-presentationerna kan vissa Ole-objektlänkar ha en relativ representation. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Se även

* Klass [String](../../../system/string/)
* Klass [OleObjectFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)