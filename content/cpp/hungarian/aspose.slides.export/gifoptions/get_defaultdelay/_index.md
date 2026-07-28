---
title: get_DefaultDelay()
second_title: Aspose.Slides C++ API-referencia
description: "Alapértelmezett késleltetési időt adja vissza [ms]. Ez az érték akkor lesz használva, ha az ISlideShowTransition::set_AdvanceAfterTime() metódust nem hívták meg. Az alapértelmezett érték 1000."
type: docs
weight: 79
url: /hu/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metódus


Az alapértelmezett késleltetési időt [ms] adja vissza. Ez az érték akkor lesz használva, ha a [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metódust nem hívták meg. Az alapértelmezett érték 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)