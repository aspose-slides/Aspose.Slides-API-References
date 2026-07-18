---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά ή ορίζει εάν πρέπει να συμπεριληφθούν οι κρυφές διαφάνειες.
type: docs
weight: 40
url: /el/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) μέθοδος

Ανακτά ή ορίζει εάν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Δείτε επίσης

* Κλάση [PresentationAnimationsGenerator](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)