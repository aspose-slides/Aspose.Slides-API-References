--- 
title: set_SlideShowType()
second_title: Aspose.Slides para C++ Referência da API
description: "Define o tipo de apresentação de slides. Representado pelos seguintes ancestrais de SlideShowType: BrowsedAtKiosk, PresentedBySpeaker e BrowsedByIndividual"
type: docs
weight: 14
url: /pt/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) método

Define o tipo de apresentação de slides. Representado pelos seguintes [SlideShowType](../../slideshowtype/) ancestrais: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) e [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
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

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlideShowType](../../slideshowtype/)
* Classe [SlideShowSettings](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)