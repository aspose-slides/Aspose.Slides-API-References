---
title: get_TransitionFps()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le FPS de transition [frames/sec] La valeur par défaut est 25.
type: docs
weight: 53
url: /fr/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() méthode

Obtient le FPS de transition [frames/sec] La valeur par défaut est 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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