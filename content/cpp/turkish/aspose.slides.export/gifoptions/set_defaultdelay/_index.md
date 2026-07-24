---
title: set_DefaultDelay()
second_title: Aspose.Slides için C++ API Referansı
description: "Varsayılan gecikme süresi [ms] ayarlar. Bu değer, ISlideShowTransition::set_AdvanceAfterTime() yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir."
type: docs
weight: 92
url: /tr/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) yöntem


Varsayılan gecikme süresini [ms] olarak ayarlar. Bu değer, [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## İlgili

* Sınıf [GifOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)