---
title: set_TargetSection()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví objekt sekce, na který odkazuje objekt Section Zoom. Zapište ISection.
type: docs
weight: 14
url: /cs/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metoda

Nastaví objekt sekce, na který odkazuje objekt [Section](../../section/) Zoom. Zapište [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
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