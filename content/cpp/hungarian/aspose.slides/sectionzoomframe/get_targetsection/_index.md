---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri azt a szekcióobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Olvassa el az ISection-et.
type: docs
weight: 1
url: /hu/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metódus

Lekéri azt a szekcióobjektumot, amelyhez a [Section](../../section/) Zoom objektum kapcsolódik. Olvassa el a [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Megjegyzések

A következő példa bemutatja a cél szakasz módosítását, és új képet hoz létre a szekciózoom objektumhoz:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Kapcsolódó elemek

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [ISection](../../isection/)
* osztály [SectionZoomFrame](../)
* névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)