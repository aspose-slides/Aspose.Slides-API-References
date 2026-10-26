---
title: set_DefaultDelay()
second_title: Aspose.Slides için C++ API Referansı
description: "Varsayılan gecikme süresini [ms] ayarlar. Bu değer, ISlideShowTransition::set_AdvanceAfterTime() metodu çağrılmadıysa kullanılacaktır. Varsayılan değer 1000."
type: docs
weight: 92
url: /tr/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metodu

Varsayılan gecikme süresini [ms] ayarlar. Bu değer, [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metodu çağrılmadıysa kullanılacaktır. Varsayılan değer 1000'dir.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Açıklamalar


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ayrıca Bakınız

* Sınıf [IGifOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)