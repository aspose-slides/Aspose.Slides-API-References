---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Referansı
description: "Varsayılan gecikme süresini [ms] alır. Bu değer, ISlideShowTransition::set_AdvanceAfterTime() yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir."
type: docs
weight: 79
url: /tr/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metodu

Varsayılan gecikme süresini [ms] alır. Bu değer, [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Ayrıca Bakınız

* Sınıf [GifOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)