---
title: get_DefaultDelay()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Λαμβάνει την προεπιλεγμένη χρονική καθυστέρηση [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν η μέθοδος ISlideShowTransition::set_AdvanceAfterTime() δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000."
type: docs
weight: 79
url: /el/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() μέθοδος


Λαμβάνει την προεπιλεγμένη τιμή καθυστέρησης [ms]. Η τιμή αυτή θα χρησιμοποιηθεί εάν η μέθοδος [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) δεν κλήθηκε. Η προεπιλεγμένη τιμή είναι 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Παρατηρήσεις



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