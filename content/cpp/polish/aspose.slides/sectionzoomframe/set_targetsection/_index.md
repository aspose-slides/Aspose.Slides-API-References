---
title: set_TargetSection()
second_title: Aspose.Slides dla C++ referencja API
description: Ustawia obiekt sekcji, do którego odwołuje się obiekt Section Zoom. Zapisz ISection.
type: docs
weight: 14
url: /pl/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metoda

Ustawia obiekt sekcji, do którego odwołuje się obiekt [Section](../../section/) Zoom. Zapisz [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Uwagi

Następny przykład pokazuje zmianę docelowej sekcji i tworzy nowy obraz dla obiektu przybliżenia sekcji:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISection](../../isection/)
* Klasa [SectionZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)