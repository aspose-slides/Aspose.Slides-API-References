---
title: get_SlideShowType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Získá typ prezentace. Reprezentováno následujícími předky SlideShowType: BrowsedAtKiosk, PresentedBySpeaker a BrowsedByIndividual"
type: docs
weight: 1
url: /cs/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metoda


Získá typ prezentace. Reprezentováno následujícími [SlideShowType](../../slideshowtype/) předky: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) a [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>();

// nastavit typ "Prohlíženo na kiosku (celá obrazovka)"

// nastavit typ "Prohlíženo jednotlivcem (okno)"

// nastavit typ "Prezentováno přednášejícím (celá obrazovka)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [SlideShowType](../../slideshowtype/)
* Třída [SlideShowSettings](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)