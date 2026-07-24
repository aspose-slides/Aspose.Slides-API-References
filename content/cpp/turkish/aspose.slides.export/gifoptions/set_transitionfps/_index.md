---
title: set_TransitionFps()
second_title: Aspose.Slides için C++ API Referansı
description: Geçiş FPS [çerçeve/sn] ayarlar. Varsayılan değer 25'tir.
type: docs
weight: 66
url: /tr/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) yöntemi


Geçiş FPS [çerçeve/sn] ayarlar. Varsayılan değer 25'tir.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Bakınız

* Sınıf [GifOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)