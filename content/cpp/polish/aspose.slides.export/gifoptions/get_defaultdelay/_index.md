---
title: get_DefaultDelay()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Pobiera domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda ISlideShowTransition::set_AdvanceAfterTime() nie została wywołana. Wartość domyślna wynosi 1000."
type: docs
weight: 79
url: /pl/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metoda


Pobiera domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Wartość domyślna wynosi 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
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