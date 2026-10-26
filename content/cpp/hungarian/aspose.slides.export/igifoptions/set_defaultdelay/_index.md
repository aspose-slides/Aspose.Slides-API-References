---
title: set_DefaultDelay()
second_title: Aspose.Slides C++ API Referenciája
description: "Beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha az ISlideShowTransition::set_AdvanceAfterTime() metódus nem lett meghívva. Az alapértelmezett érték 1000."
type: docs
weight: 92
url: /hu/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metódus


Beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha a(z) [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metódus nem lett meghívva. Az alapértelmezett érték 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
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