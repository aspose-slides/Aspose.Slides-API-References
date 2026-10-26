---
title: get_TargetSection()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar sektionens objekt som Section Zoom-objektet är länkat till. Läs ISection.
type: docs
weight: 1
url: /sv/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() metod


Hämtar sektionens objekt som [Section](../../section/) Zoom-objektet är länkat till. Läs [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Anmärkningar


Detta exempel visar hur man ändrar målsektionen och skapar en ny bild för sektionens zoom-objekt: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISection](../../isection/)
* Klass [ISectionZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)