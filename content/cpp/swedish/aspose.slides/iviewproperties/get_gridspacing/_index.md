---
title: get_GridSpacing()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs float.
type: docs
weight: 92
url: /sv/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metod


Returnerar rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Anmärkningar


Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter). 

Följande exempelprogram visar hur man ändrar rasteravståndet i en PowerPoint-presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)