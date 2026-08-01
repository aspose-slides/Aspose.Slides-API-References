---
title: set_SlideShowType()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het diavoorstellingstype in. Wordt vertegenwoordigd door de volgende SlideShowType voorouders: BrowsedAtKiosk, PresentedBySpeaker en BrowsedByIndividual"
type: docs
weight: 14
url: /nl/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) methode


Stelt het type diavoorstelling in. Wordt vertegenwoordigd door de volgende [SlideShowType](../../slideshowtype/) voorouders: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) en [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
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