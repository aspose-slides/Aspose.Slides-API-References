---
title: get_DefaultDelay()
second_title: Aspose.Slides für C++ API Referenz
description: "Ruft die Standardverzögerungszeit [ms] ab. Dieser Wert wird verwendet, wenn die ISlideShowTransition::set_AdvanceAfterTime() Methode nicht aufgerufen wurde. Der Standardwert ist 1000."
type: docs
weight: 79
url: /de/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() Methode

Liefert die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn die [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) Methode nicht aufgerufen wurde. Der Standardwert ist 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Anmerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Siehe auch

* Klasse [IGifOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)