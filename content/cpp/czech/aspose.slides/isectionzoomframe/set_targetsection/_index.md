---
title: set_TargetSection()
second_title: Aspose.Slides pro C++ API referenci
description: Nastavuje objekt sekce, ke které je propojen objekt Section Zoom. Zapište ISection.
type: docs
weight: 14
url: /cs/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metoda


Nastavuje objekt sekce, ke které je objekt [Section](../../section/) Zoom propojen. Zapište [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Poznámky


Tento příklad ukazuje změnu cílové sekce a vytváří nový obrázek pro objekt zoom sekce: 
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
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)