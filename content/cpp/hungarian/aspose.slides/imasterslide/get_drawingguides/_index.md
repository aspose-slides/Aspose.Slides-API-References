---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy gyűjteményt a mester dián lévő rajzsegélyekről. Csak olvasható IDrawingGuidesCollection
type: docs
weight: 105
url: /hu/aspose.slides/imasterslide/get_drawingguides/
---
## IMMasterSlide::get_DrawingGuides() metódus


Visszaad egy gyűjteményt a mester dia rajzsegényeiről. Csak olvasható [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Új függőleges rajzsegéd hozzáadása a diaközép jobb oldalához
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [IMasterSlide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)