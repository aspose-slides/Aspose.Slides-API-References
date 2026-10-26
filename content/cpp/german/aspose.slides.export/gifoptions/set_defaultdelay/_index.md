---
title: set_DefaultDelay()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn die ISlideShowTransition::set_AdvanceAfterTime() Methode nicht aufgerufen wurde. Der Standardwert ist 1000."
type: docs
weight: 92
url: /de/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) Methode

Setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn die [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) Methode nicht aufgerufen wurde. Der Standardwert ist 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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
* Bibliothek [Aspose.Slides](../../../)