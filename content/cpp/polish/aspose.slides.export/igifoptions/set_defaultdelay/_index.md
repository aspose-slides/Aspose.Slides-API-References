---
title: set_DefaultDelay()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda ISlideShowTransition::set_AdvanceAfterTime() nie została wywołana. Domyślna wartość to 1000."
type: docs
weight: 92
url: /pl/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metoda


Ustawia domyślny czas opóźnienia [ms]. Ta wartość będzie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Domyślna wartość wynosi 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
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