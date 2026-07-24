---
title: get_SlideShowType()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ruft den Diashowtyp ab. Wird von den folgenden SlideShowType-Vorfahren dargestellt: BrowsedAtKiosk, PresentedBySpeaker und BrowsedByIndividual"
type: docs
weight: 1
url: /de/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() Methode

Ruft den Diashowtyp ab. Wird von den folgenden [SlideShowType](../../slideshowtype/) Vorfahren dargestellt: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) und [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Hinweise


```cpp
auto pres = System::MakeObject<Presentation>();

// um den Typ "Browsed at a kiosk (full screen)" festzulegen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// um den Typ "Browsed by individual (window)" festzulegen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// um den Typ "Presented by a speaker (full screen)" festzulegen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SlideShowType](../../slideshowtype/)
* Klasse [SlideShowSettings](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)