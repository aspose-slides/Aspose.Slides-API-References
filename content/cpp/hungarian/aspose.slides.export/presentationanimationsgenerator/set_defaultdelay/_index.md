---
title: set_DefaultDelay()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja az alapértelmezett késleltetési időt [ms].
type: docs
weight: 14
url: /hu/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) metódus


Beállítja az alapértelmezett késleltetési időt [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
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