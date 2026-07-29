---
title: get_DefaultDelay()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar standardfördröjningstid [ms]. Detta värde kommer att användas om ISlideShowTransition::set_AdvanceAfterTime() metoden inte anropades. Standardvärdet är 1000."
type: docs
weight: 79
url: /sv/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metod


Hämtar standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/)-metoden inte anropades. Standardvärdet är 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Se även

* Klass [IGifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)