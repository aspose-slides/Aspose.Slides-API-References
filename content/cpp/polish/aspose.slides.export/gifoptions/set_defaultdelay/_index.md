---
title: set_DefaultDelay()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda ISlideShowTransition::set_AdvanceAfterTime() nie została wywołana. Domyślna wartość to 1000."
type: docs
weight: 92
url: /pl/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metoda

Ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Domyślna wartość to 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Zobacz także

* Klasa [GifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)