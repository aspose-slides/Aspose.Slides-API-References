---
title: set_TargetSection()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in sektionobjektet som Section Zoom-objektet är länkat till. Skriv ISection.
type: docs
weight: 14
url: /sv/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metod


Ställer in sektionobjektet som [Section](../../section/) Zoom-objektet är länkat till. Skriv [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Anmärkningar


Det här exemplet visar hur man ändrar målsektionen och skapar en ny bild för sektion-zoom-objektet: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [ISection](../../isection/)
* klass [ISectionZoomFrame](../)
* namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)