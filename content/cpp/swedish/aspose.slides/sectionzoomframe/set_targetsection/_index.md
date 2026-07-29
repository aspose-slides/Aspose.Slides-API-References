---
title: set_TargetSection()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in sektionobjektet som Section Zoom-objektet länkar till. Skriv ISection.
type: docs
weight: 14
url: /sv/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metod


Ställer in sektionobjektet som [Section](../../section/) Zoom-objektet länkar till. Skriv [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Anmärkningar


Nästa exempel visar hur man ändrar målssektion och skapar en ny bild för sektion zoom-objektet: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISection](../../isection/)
* Klass [SectionZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)