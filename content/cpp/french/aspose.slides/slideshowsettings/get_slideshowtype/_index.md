---
title: get_SlideShowType()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient le type du diaporama. Représenté par les ancêtres SlideShowType suivants: BrowsedAtKiosk, PresentedBySpeaker et BrowsedByIndividual"
type: docs
weight: 1
url: /fr/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() méthode


Obtient le type du diaporama. Représenté par les ancêtres [SlideShowType](../../slideshowtype/) suivants: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) et [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();

// pour définir le type "Navigué sur un kiosque (plein écran)"
// pour définir le type "Navigué par un individu (fenêtre)"
// pour définir le type "Présenté par un orateur (plein écran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// to set "Browsed by individual (window)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// to set "Presented by a speaker (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlideShowType](../../slideshowtype/)
* Classe [SlideShowSettings](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)