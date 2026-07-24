---
title: set_SlideShowType()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt den Folienpräsentationstyp fest. Repräsentiert durch die folgenden SlideShowType Vorfahren: BrowsedAtKiosk, PresentedBySpeaker und BrowsedByIndividual"
type: docs
weight: 14
url: /de/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) Methode


Setzt den Folienpräsentationstyp. Repräsentiert durch die folgenden [SlideShowType](../../slideshowtype/) Vorgänger: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) und [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Bemerkungen



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
* Bibliothek [Aspose.Slides](../../../)