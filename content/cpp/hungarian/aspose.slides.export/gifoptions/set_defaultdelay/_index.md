---
title: set_DefaultDelay()
second_title: Aspose.Slides C++ API Referencia
description: "Beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték akkor lesz használva, ha az ISlideShowTransition::set_AdvanceAfterTime() metódus nem lett meghívva. Az alapértelmezett érték 1000."
type: docs
weight: 92
url: /hu/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metódus


Beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték akkor lesz használva, ha a [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metódus nem lett meghívva. Az alapértelmezett érték 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Lásd még

* Osztály [GifOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)