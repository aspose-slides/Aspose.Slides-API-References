---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Referansı
description: "Varsayılan gecikme süresini [ms] alır. Bu değer, ISlideShowTransition::set_AdvanceAfterTime() yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir."
type: docs
weight: 79
url: /tr/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metodu

Varsayılan gecikme süresini [ms] alır. Bu değer, [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) yöntemi çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Diğer Bağlantılar

* Sınıf [IGifOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)