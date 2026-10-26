---
title: get_TargetSection()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera obiekt sekcji, do którego powiązany jest obiekt Section Zoom. Przeczytaj ISection.
type: docs
weight: 1
url: /pl/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() metoda

Pobiera obiekt sekcji, do którego powiązany jest obiekt [Section](../../section/) Zoom. Przeczytaj [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Uwagi

Ten przykład demonstruje zmianę sekcji docelowej i tworzy nowy obraz dla obiektu sekcji zoom:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISection](../../isection/)
* Klasa [ISectionZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)