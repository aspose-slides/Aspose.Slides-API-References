---
title: get_TargetSection()
second_title: Aspose.Slides pro referenci API C++
description: Získá objekt sekce, na který odkazuje objekt Section Zoom. Přečtěte si ISection.
type: docs
weight: 1
url: /cs/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metoda


Získá objekt sekce, na který odkazuje objekt [Section](../../section/) Zoom. Přečtěte si [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Poznámky


Následující příklad ukazuje změnu cílové sekce a vytváří nový obrázek pro objekt zoom sekce: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISection](../../isection/)
* Třída [SectionZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)