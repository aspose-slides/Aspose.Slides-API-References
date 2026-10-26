---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a rajzolási segédvonalak gyűjteményét. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 53
url: /hu/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metódus


Visszaadja a rajzolási segédvonalak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Megjegyzések


Az alábbi példakód bemutatja, hogyan lehet új rajzolási segédvonalakat hozzáadni egy PowerPoint-prezentációhoz.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Új függőleges rajzolási segédvonal hozzáadása a dia középpontjának jobb oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Új vízszintes rajzolási segédvonal hozzáadása a dia középpontja alá
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [ICommonSlideViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)