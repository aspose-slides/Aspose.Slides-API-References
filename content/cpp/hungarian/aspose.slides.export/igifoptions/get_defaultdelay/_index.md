---
title: get_DefaultDelay()
second_title: Aspose.Slides C++ API hivatkozása
description: "Alapértelmezett késleltetési időt ad [ms]. Ez az érték lesz használva, ha az ISlideShowTransition::set_AdvanceAfterTime() metódust nem hívták meg. Az alapértelmezett érték 1000."
type: docs
weight: 79
url: /hu/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metódus


Alapértelmezett késleltetési időt adja vissza [ms]. Ez az érték lesz használva, ha a [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metódust nem hívták meg. Az alapértelmezett érték 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lásd még

* Osztály [IGifOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)