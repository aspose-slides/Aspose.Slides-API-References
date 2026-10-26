---
title: get_TransitionFps()
second_title: Aspose.Slides C++ API referencia
description: Lekéri az átmenet FPS [képkocka/mp] Az alapértelmezett érték 25.
type: docs
weight: 53
url: /hu/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metódus


Lekéri az átmenet FPS [képkocka/mp] Az alapértelmezett érték 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Megjegyzések


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lásd még

* Osztály [IGifOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)