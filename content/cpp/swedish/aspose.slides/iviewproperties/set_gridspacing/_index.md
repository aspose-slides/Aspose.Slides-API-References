---
title: set_GridSpacing()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in rasteravståndet som ska användas för raster under det underliggande presentationsdokumentet, i punkter. Skriv float.
type: docs
weight: 105
url: /sv/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) metod

Ställer in rasteravståndet som ska användas för rastern underliggande presentationsdokumentet, i punkter. Skriv **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Anmärkningar

Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter).

Följande exempel kod visar hur man ändrar rasteravståndet i en PowerPoint-presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)