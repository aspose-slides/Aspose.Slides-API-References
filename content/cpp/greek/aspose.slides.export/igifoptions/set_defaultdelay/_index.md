---
title: set_DefaultDelay()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η μέθοδος ISlideShowTransition::set_AdvanceAfterTime() δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000."
type: docs
weight: 92
url: /el/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) μέθοδος


Ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) μέθοδος δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Σημειώσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Δείτε επίσης

* Κλάση [IGifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)