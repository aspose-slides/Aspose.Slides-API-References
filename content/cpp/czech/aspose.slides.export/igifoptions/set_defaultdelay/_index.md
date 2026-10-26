---
title: set_DefaultDelay()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Nastaví výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda ISlideShowTransition::set_AdvanceAfterTime() metodou. Výchozí hodnota je 1000."
type: docs
weight: 92
url: /cs/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metoda


Nastaví výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). Výchozí hodnota je 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Viz také

* Třída [IGifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)