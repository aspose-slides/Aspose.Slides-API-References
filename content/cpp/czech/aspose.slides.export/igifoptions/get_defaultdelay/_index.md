---
title: get_DefaultDelay()
second_title: Aspose.Slides pro C++ - reference API
description: "Získá výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud nebyla metoda ISlideShowTransition::set_AdvanceAfterTime() zavolána. Výchozí hodnota je 1000."
type: docs
weight: 79
url: /cs/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metoda


Získá výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud nebyla metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) zavolána. Výchozí hodnota je 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
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