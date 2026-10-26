---
title: get_SlideShowType()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het type diavoorstelling op. Vertegenwoordigd door de volgende SlideShowType voorouders: BrowsedAtKiosk, PresentedBySpeaker en BrowsedByIndividual"
type: docs
weight: 1
url: /nl/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() methode


Haalt het type diavoorstelling op. Wordt vertegenwoordigd door de volgende [SlideShowType](../../slideshowtype/) voorouders: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) en [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>();

// om het type "Browsed at a kiosk (full screen)" in te stellen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// om het type "Browsed by individual (window)" in te stellen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// om het type "Presented by a speaker (full screen)" in te stellen
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SlideShowType](../../slideshowtype/)
* Klasse [SlideShowSettings](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)