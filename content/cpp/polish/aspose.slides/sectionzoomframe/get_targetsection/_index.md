---
title: get_TargetSection()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera obiekt sekcji, do którego odwołuje się obiekt Section Zoom. Zobacz ISection.
type: docs
weight: 1
url: /pl/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metoda

Pobiera obiekt sekcji, do którego odwołuje się obiekt [Section](../../section/) Zoom. Zobacz [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Uwagi

Następny przykład pokazuje zmianę docelowej sekcji i tworzy nowy obraz dla obiektu powiększenia sekcji:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISection](../../isection/)
* Klasa [SectionZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)