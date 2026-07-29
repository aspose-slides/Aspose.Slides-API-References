---
title: set_DefaultDelay()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in standardfördröjningstid [ms]. Detta värde kommer att användas om metoden ISlideShowTransition::set_AdvanceAfterTime() inte anropades. Standardvärdet är 1000."
type: docs
weight: 92
url: /sv/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metod

Ställer in standardfördröjningstid [ms]. Detta värde kommer att användas om metoden [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) inte anropades. Standardvärdet är 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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