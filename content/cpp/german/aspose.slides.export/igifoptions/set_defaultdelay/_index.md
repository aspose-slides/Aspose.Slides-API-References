---
title: set_DefaultDelay()
second_title: Aspose.Slides für C++ API Referenz
description: "Setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn die ISlideShowTransition::set_AdvanceAfterTime()-Methode nicht aufgerufen wurde. Der Standardwert ist 1000."
type: docs
weight: 92
url: /de/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) method


Setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn die [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/)-Methode nicht aufgerufen wurde. Der Standardwert ist 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
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