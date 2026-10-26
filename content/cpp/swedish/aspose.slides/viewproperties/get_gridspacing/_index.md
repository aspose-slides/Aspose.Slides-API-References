---
title: get_GridSpacing()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar rutavståndet som ska användas för rutnätet underliggande presentationsdokumentet, i punkter. Läs float.
type: docs
weight: 92
url: /sv/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() metod


Returnerar rutavståndet som ska användas för rutnätet underliggande presentationsdokumentet, i punkter. Läs **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Anmärkningar


Rutavståndsvärdet måste vara ett positivt tal. Det vanliga värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter). 

Följande exempelprogram visar hur man ändrar rutavståndet i en PowerPoint-presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Se också

* Klass [ViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)