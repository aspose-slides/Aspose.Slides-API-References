---
title: get_SlideShowType()
second_title: Aspose.Slides για C++ - Αναφορά API
description: "Λαμβάνει τον τύπο παρουσίασης διαφανειών. Αναπαρίσταται από τους παρακάτω προγόνους SlideShowType: BrowsedAtKiosk, PresentedBySpeaker και BrowsedByIndividual"
type: docs
weight: 1
url: /el/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() μέθοδος

Παίρνει τον τύπο παρουσίασης διαφανειών. Αναπαρίσταται από τους παρακάτω [SlideShowType](../../slideshowtype/) προγόνους: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) και [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();

// για να ορίσετε τον τύπο "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// για να ορίσετε τον τύπο "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// για να ορίσετε τον τύπο "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [SlideShowType](../../slideshowtype/)
* Κλάση [SlideShowSettings](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)