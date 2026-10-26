---
title: get_SlideShowType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera typ pokazu slajdów. Reprezentowany przez następujących przodków SlideShowType: BrowsedAtKiosk, PresentedBySpeaker i BrowsedByIndividual"
type: docs
weight: 1
url: /pl/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metoda

Pobiera typ pokazu slajdów. Reprezentowany przez następujących [SlideShowType](../../slideshowtype/) przodków: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) i [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();

// aby ustawić typ "Przeglądane w kiosku (pełny ekran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// aby ustawić typ "Przeglądane przez indywidualnego użytkownika (okno)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// aby ustawić typ "Prezentowane przez prelegenta (pełny ekran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [SlideShowType](../../slideshowtype/)
* Klasa [SlideShowSettings](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)