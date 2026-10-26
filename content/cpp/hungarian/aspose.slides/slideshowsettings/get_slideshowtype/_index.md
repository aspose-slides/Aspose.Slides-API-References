---
title: get_SlideShowType()
second_title: Aspose.Slides C++ API-referencia
description: "Lekéri a diavetítés típusát. A következő SlideShowType ősök: BrowsedAtKiosk, PresentedBySpeaker és BrowsedByIndividual"
type: docs
weight: 1
url: /hu/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metódus

Visszaadja a diavetítés típusát. A következő [SlideShowType](../../slideshowtype/) ősök: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) és [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [SlideShowType](../../slideshowtype/)
* Osztály [SlideShowSettings](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)