---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar eller anger om dolda bilder ska inkluderas.
type: docs
weight: 27
url: /sv/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metod

Hämtar eller anger om dolda bilder ska inkluderas.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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