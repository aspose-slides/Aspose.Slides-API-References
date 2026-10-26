---
title: get_DefaultDelay()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Λαμβάνει το προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η μέθοδος ISlideShowTransition::set_AdvanceAfterTime() δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000."
type: docs
weight: 79
url: /el/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() μέθοδος


Λαμβάνει το προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) μέθοδος δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
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