---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API Referansı
description: Geçiş FPS'sini [frames/sec] ayarlar. Varsayılan değer 25'tir.
type: docs
weight: 66
url: /tr/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) metodu


Geçiş FPS'sini [frames/sec] ayarlar. Varsayılan değer 25'tir.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)