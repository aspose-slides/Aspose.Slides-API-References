---
title: get_DefaultDelay()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar standardfördröjningstid [ms]. Detta värde kommer att användas om metoden ISlideShowTransition::set_AdvanceAfterTime() inte anropades. Standardvärdet är 1000."
type: docs
weight: 79
url: /sv/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metod


Hämtar standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/)-metoden inte anropades. Standardvärdet är 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Se även

* Klass [GifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)