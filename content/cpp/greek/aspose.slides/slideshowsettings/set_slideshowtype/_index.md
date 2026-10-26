---
title: set_SlideShowType()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ορίζει τον τύπο παρουσίασης. Αντιπροσωπεύεται από τους παρακάτω προγόνους SlideShowType: BrowsedAtKiosk, PresentedBySpeaker και BrowsedByIndividual"
type: docs
weight: 14
url: /el/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) μέθοδος

Ορίζει τον τύπο παρουσίασης. Αντιπροσωπεύεται από τους παρακάτω [SlideShowType](../../slideshowtype/) προγόνους: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) και [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();

// για ορισμό τύπου "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// για ορισμό τύπου "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// για ορισμό τύπου "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [SlideShowType](../../slideshowtype/)
* Κλάση [SlideShowSettings](../)
* Ονοματοχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)