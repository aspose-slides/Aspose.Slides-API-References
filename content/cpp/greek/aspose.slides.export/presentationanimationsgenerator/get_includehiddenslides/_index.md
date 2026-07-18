---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά ή ορίζει αν πρέπει να συμπεριληφθούν οι κρυφές διαφάνειες.
type: docs
weight: 27
url: /el/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const μέθοδος


Ανακτά ή ορίζει εάν πρέπει να συμπεριληφθούν οι κρυφές διαφάνειες.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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