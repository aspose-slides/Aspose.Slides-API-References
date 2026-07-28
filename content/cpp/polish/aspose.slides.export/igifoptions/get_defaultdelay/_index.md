---
title: get_DefaultDelay()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Zwraca domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda ISlideShowTransition::set_AdvanceAfterTime() nie została wywołana. Domyślna wartość to 1000."
type: docs
weight: 79
url: /pl/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metoda

Zwraca domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Domyślna wartość to 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## Zobacz także

* Klasa [IGifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)