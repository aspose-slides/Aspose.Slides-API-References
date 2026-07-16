---
title: get_TransitionFps()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les FPS de transition [images/sec]. La valeur par défaut est 25.
type: docs
weight: 53
url: /fr/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() method

Obtient les FPS de transition [images/sec]. La valeur par défaut est 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Voir aussi

* Classe [IGifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)