---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API Referenciája
description: Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezési dián. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 118
url: /hu/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() metódus


Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezési dián. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Az új függőleges rajzolósegédvonal hozzáadása a dia közepének bal oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [LayoutSlide](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)