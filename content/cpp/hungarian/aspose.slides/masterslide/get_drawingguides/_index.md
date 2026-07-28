---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy gyűjteményt a mesterdia rajzolási segédvonalairól. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 170
url: /hu/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() metódus


Visszaad egy gyűjteményt a mesterdia rajzolási segédvonalairól. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Az új függőleges rajzolási segédvonal hozzáadása a dia közepének jobb oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [MasterSlide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)