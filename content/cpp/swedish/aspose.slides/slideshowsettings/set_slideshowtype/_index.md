---
title: set_SlideShowType()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in bildspels-typen. Representeras av följande SlideShowType-förfäder: BrowsedAtKiosk, PresentedBySpeaker och BrowsedByIndividual"
type: docs
weight: 14
url: /sv/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metod

Ställer in bildspels-typen. Representeras av följande [SlideShowType](../../slideshowtype/) förfäder: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) och [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>();

// för att sätta "Browsed at a kiosk (full screen)"-typen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// för att sätta "Browsed by individual (window)"-typen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// för att sätta "Presented by a speaker (full screen)"-typen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SlideShowType](../../slideshowtype/)
* Klass [SlideShowSettings](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)