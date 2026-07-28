---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Referencia
description: Az alapértelmezett késleltetési időt [ms] adja vissza.
type: docs
weight: 1
url: /hu/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const metódus


Az alapértelmezett késleltetési időt [ms] adja vissza.

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Lásd még

* Osztály [PresentationAnimationsGenerator](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)