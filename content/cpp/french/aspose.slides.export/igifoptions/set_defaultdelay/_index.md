---
title: set_DefaultDelay()
second_title: Référence API Aspose.Slides pour C++
description: "Définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si la méthode ISlideShowTransition::set_AdvanceAfterTime() n'a pas été appelée. La valeur par défaut est 1000."
type: docs
weight: 92
url: /fr/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) méthode


Définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si la méthode [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) n'a pas été appelée. La valeur par défaut est 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Voir aussi

* Classe [IGifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)