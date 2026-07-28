---
title: set_SlideShowType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Ustawia typ pokazu slajdów. Reprezentowany przez następujących przodków SlideShowType: BrowsedAtKiosk, PresentedBySpeaker i BrowsedByIndividual"
type: docs
weight: 14
url: /pl/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) method

Ustawia typ pokazu slajdów. Reprezentowany przez następujących [SlideShowType](../../slideshowtype/) przodków: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) i [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();

// aby ustawić typ "Przeglądany w kiosku (pełny ekran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// aby ustawić typ "Przeglądany przez indywidualnego użytkownika (okno)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// aby ustawić typ "Prezentowany przez prelegenta (pełny ekran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [SlideShowType](../../slideshowtype/)
* Klasa [SlideShowSettings](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)