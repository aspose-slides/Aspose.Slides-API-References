---
title: get_TargetSection()
second_title: Aspose.Slides C++ API Referenciája
description: Lekéri a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Olvassa el ISection.
type: docs
weight: 1
url: /hu/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() metódus

Lekéri a szakasz objektumot, amelyhez a [Section](../../section/) Zoom objektum kapcsolódik. Olvassa [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Megjegyzések

Ez a példa bemutatja a célszakasz megváltoztatását, és új képet hoz létre a szakasz zoom objektumhoz:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISection](../../isection/)
* Osztály [ISectionZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)