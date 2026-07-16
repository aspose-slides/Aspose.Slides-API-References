---
title: get_DefaultDelay()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Obtient le temps de retard par défaut [ms]. Cette valeur sera utilisée si la méthode ISlideShowTransition::set_AdvanceAfterTime() n'a pas été appelée. La valeur par défaut est 1000."
type: docs
weight: 79
url: /fr/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() méthode

Obtient le délai par défaut [ms]. Cette valeur sera utilisée si la méthode [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) n’a pas été appelée. La valeur par défaut est 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Remarques


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Voir aussi

* Classe [GifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)