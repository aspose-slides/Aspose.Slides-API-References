---
title: get_DefaultDelay()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τον προεπιλεγμένο χρόνο καθυστέρησης [ms].
type: docs
weight: 1
url: /el/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const μέθοδος

Λαμβάνει το προεπιλεγμένο χρόνο καθυστέρησης [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Σχόλια

```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```

## Δείτε επίσης

* Τάξη [PresentationAnimationsGenerator](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)