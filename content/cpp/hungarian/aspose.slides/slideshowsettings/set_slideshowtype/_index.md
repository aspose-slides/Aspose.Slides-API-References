---
title: set_SlideShowType()
second_title: Aspose.Slides C++ API referencia
description: "Beállítja a diavetítés típusát. A következő SlideShowType ősei: BrowsedAtKiosk, PresentedBySpeaker és BrowsedByIndividual"
type: docs
weight: 14
url: /hu/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metódus


Beállítja a diavetítés típusát. A következő [SlideShowType](../../slideshowtype/) ősei: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) és [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>();

// a "Browsed at a kiosk (full screen)" típus beállításához
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// a "Browsed by individual (window)" típus beállításához
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// a "Presented by a speaker (full screen)" típus beállításához
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [SlideShowType](../../slideshowtype/)
* Osztály [SlideShowSettings](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)