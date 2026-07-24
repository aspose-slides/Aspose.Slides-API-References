---
title: get_DefaultDelay()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Standardverzögerungszeit [ms] zurück. Dieser Wert wird verwendet, wenn die ISlideShowTransition::set_AdvanceAfterTime() Methode nicht aufgerufen wurde. Der Standardwert ist 1000."
type: docs
weight: 79
url: /de/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() Methode


Gibt die Standardverzögerungszeit [ms] zurück. Dieser Wert wird verwendet, wenn die [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) Methode nicht aufgerufen wurde. Der Standardwert ist 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Siehe auch

* Klasse [GifOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)