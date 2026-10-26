---
title: set_TargetSection()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja azt a szekcióobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Írja ISection.
type: docs
weight: 14
url: /hu/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metódus


Beállítja a szekcióobjektumot, amelyhez a [Section](../../section/) Zoom objektum kapcsolódik. Írja [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Megjegyzések


Ez a példa bemutatja a cél szekció módosítását, és új képet hoz létre a szekció zoom objektumhoz: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISection](../../isection/)
* Osztály [ISectionZoomFrame](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)