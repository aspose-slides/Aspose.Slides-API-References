---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar eller anger om dolda bilder ska inkluderas.
type: docs
weight: 40
url: /sv/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metod


Hämtar eller anger om dolda bilder ska inkluderas.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Se även

* Klass [PresentationAnimationsGenerator](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)