---
title: get_SlideShowType()
second_title: Aspose.Slides per C++ Riferimento API
description: "Restituisce il tipo di presentazione. Rappresentato dai seguenti antenati di SlideShowType: BrowsedAtKiosk, PresentedBySpeaker e BrowsedByIndividual"
type: docs
weight: 1
url: /it/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metodo

Restituisce il tipo di presentazione. Rappresentato dai seguenti antenati [SlideShowType](../../slideshowtype/): [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) e [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();

// per impostare il tipo "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// per impostare il tipo "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// per impostare il tipo "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlideShowType](../../slideshowtype/)
* Classe [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)