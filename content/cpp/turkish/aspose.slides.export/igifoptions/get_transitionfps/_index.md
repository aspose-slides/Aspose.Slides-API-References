---
title: get_TransitionFps()
second_title: Aspose.Slides için C++ API Referansı
description: Geçiş FPS'sini alır [frames/sec] Varsayılan değer 25'tir.
type: docs
weight: 53
url: /tr/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metodu

Geçiş FPS'sini alır [frames/sec] Varsayılan değer 25'tir.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## Ayrıca Bakınız

* Sınıf [IGifOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)