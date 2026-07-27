---
title: set_IncludeHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Obtém ou define se os slides ocultos devem ser incluídos.
type: docs
weight: 40
url: /pt/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) método


Obtém ou define se os slides ocultos devem ser incluídos.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Ver também

* Classe [PresentationAnimationsGenerator](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)