---
title: set_SlideShowType()
second_title: Aspose.Slides pro C++ – API Reference
description: "Nastavuje typ prezentace. Je reprezentován následujícími předky SlideShowType: BrowsedAtKiosk, PresentedBySpeaker a BrowsedByIndividual"
type: docs
weight: 14
url: /cs/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metoda

Nastavuje typ prezentace. Je reprezentován následujícími [SlideShowType](../../slideshowtype/) předky: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) a [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Poznámky


```cpp
auto pres = System::MakeObject<Presentation>();

// pro nastavení typu "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// pro nastavení typu "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// pro nastavení typu "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SlideShowType](../../slideshowtype/)
* Class [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)