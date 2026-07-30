---
title: get_TargetSection()
second_title: Aspose.Slides pro C++ API Reference
description: Získá objekt sekce, ke které je objekt Section Zoom připojen. Přečtěte si ISection.
type: docs
weight: 1
url: /cs/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() metoda


Získá objekt sekce, ke které je objekt [Section](../../section/) Zoom připojen. Přečtěte si [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Poznámky


Tento příklad ukazuje změnu cílové sekce a vytvoření nového obrázku pro objekt zoom sekce: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISection](../../isection/)
* Třída [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)