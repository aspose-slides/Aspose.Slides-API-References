---
title: set_DefaultDelay()
second_title: Αναφορά API Aspose.Slides για C++
description: "Ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η μέθοδος ISlideShowTransition::set_AdvanceAfterTime() δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000."
type: docs
weight: 92
url: /el/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) μέθοδος

Ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) μέθοδος δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Δείτε επίσης

* Κλάση [GifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)