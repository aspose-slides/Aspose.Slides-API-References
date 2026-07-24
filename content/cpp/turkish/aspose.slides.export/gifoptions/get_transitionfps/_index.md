---
title: get_TransitionFps()
second_title: Aspose.Slides için C++ API Referansı
description: Geçiş FPS'sini alır [frames/sec] Varsayılan değer 25'tir.
type: docs
weight: 53
url: /tr/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metodu


Geçiş FPS'sini alır [frames/sec] Varsayılan değer 25'tir.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Açıklamalar


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## İlgili

* Sınıf [GifOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)