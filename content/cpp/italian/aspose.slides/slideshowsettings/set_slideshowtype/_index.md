---
title: set_SlideShowType()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta il tipo di presentazione. Rappresentato dai seguenti antenati di SlideShowType: BrowsedAtKiosk, PresentedBySpeaker e BrowsedByIndividual"
type: docs
weight: 14
url: /it/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metodo

Imposta il tipo di presentazione. Rappresentato dai seguenti [SlideShowType](../../slideshowtype/) antenati: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) e [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
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
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)