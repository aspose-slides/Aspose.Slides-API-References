---
title: get_SlideShowType()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar bildspels-typen. Representeras av följande SlideShowType-förfäder: BrowsedAtKiosk, PresentedBySpeaker och BrowsedByIndividual"
type: docs
weight: 1
url: /sv/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metod

Hämtar bildspels-typen. Representeras av följande [SlideShowType](../../slideshowtype/) förfäder: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) och [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>();

// för att ange typen "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// för att ange typen "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// för att ange typen "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SlideShowType](../../slideshowtype/)
* Klass [SlideShowSettings](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)