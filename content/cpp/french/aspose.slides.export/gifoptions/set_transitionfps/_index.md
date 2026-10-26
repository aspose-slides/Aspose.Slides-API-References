---
title: set_TransitionFps()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le FPS de transition [images/s] La valeur par défaut est 25.
type: docs
weight: 66
url: /fr/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) méthode


Définit le FPS de transition [images/s] La valeur par défaut est 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Voir aussi

* Classe [GifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)