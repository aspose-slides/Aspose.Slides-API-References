---
title: get_Handout()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie combien de diapositives et dans quel ordre elles seront placées sur la page HandoutType.
type: docs
weight: 1
url: /fr/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const method

Spécifie combien de diapositives et dans quel ordre seront placées sur la page [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Remarques

La valeur par défaut est **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Voir aussi

* Enum [HandoutType](../../handouttype/)
* Classe [HandoutLayoutingOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)