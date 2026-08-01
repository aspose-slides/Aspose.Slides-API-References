---
title: get_DefaultDelay()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de standaardvertragingstijd op [ms]. Deze waarde wordt gebruikt als de ISlideShowTransition::set_AdvanceAfterTime() methode niet werd aangeroepen. De standaardwaarde is 1000."
type: docs
weight: 79
url: /nl/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() methode


Retourneert de standaardvertragingstijd [ms]. Deze waarde wordt gebruikt als de [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) methode niet werd aangeroepen. De standaardwaarde is 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zie ook

* Klasse [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)