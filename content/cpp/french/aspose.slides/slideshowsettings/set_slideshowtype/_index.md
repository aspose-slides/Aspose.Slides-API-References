---
title: set_SlideShowType()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit le type de diaporama. Représenté par les ancêtres SlideShowType suivants : BrowsedAtKiosk, PresentedBySpeaker et BrowsedByIndividual"
type: docs
weight: 14
url: /fr/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) méthode

Définit le type de diaporama. Représenté par les ancêtres [SlideShowType](../../slideshowtype/) suivants : [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) et [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();

// pour définir le type "Navigué sur un kiosque (plein écran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// pour définir le type "Navigué par un individu (fenêtre)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// pour définir le type "Présenté par un intervenant (plein écran)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlideShowType](../../slideshowtype/)
* Classe [SlideShowSettings](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)