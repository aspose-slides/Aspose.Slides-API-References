---
title: set_TargetSection()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia obiekt sekcji, z którym powiązany jest obiekt Section Zoom. Zapisz ISection.
type: docs
weight: 14
url: /pl/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metoda

Ustawia obiekt sekcji, z którym powiązany jest obiekt [Section](../../section/) Zoom. Zapisz [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Uwagi

Ten przykład demonstruje zmianę docelowej sekcji i tworzy nowy obraz dla obiektu przybliżenia sekcji:
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