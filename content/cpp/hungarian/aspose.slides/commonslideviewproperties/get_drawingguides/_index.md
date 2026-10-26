---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a rajzoló segédvonalak gyűjteményét. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 53
url: /hu/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() metódus

Visszaadja a rajzoló segéveket tartalmazó gyűjteményt. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Megjegyzések

Az alábbi minta kód bemutatja, hogyan lehet új rajzoló segéveket hozzáadni egy PowerPoint bemutatóhoz.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Az új függőleges rajzoló segédvonal hozzáadása a dia középpontjának jobb oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Az új vízszintes rajzoló segédvonal hozzáadása a dia középpontja alá
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [CommonSlideViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)