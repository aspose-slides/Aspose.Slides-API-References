---
title: set_DefaultDelay()
second_title: Aspose.Slides για την Αναφορά API C++
description: Ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms].
type: docs
weight: 14
url: /el/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) μέθοδος


Ορίζει το προεπιλεγμένο χρόνο καθυστέρησης [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Δείτε επίσης

* Κλάση [PresentationAnimationsGenerator](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)