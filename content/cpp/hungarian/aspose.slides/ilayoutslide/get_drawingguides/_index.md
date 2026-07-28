---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezési dián. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 79
url: /hu/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() method


Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezési dián. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Az új függőleges rajzolási segédvonal hozzáadása a dia közepének bal oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [ILayoutSlide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)