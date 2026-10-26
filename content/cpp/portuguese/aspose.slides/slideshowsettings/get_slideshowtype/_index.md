---
title: get_SlideShowType()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém o tipo de apresentação de slides. Representado pelos seguintes ancestrais de SlideShowType: BrowsedAtKiosk, PresentedBySpeaker e BrowsedByIndividual"
type: docs
weight: 1
url: /pt/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() método

Obtém o tipo de apresentação de slides. Representado pelos seguintes [SlideShowType](../../slideshowtype/) ancestrais: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) e [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>();

// para definir o tipo "Navegado em um quiosque (tela cheia)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// para definir o tipo "Navegado por indivíduo (janela)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// para definir o tipo "Apresentado por um palestrante (tela cheia)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlideShowType](../../slideshowtype/)
* Classe [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)