---
title: set_TransitionFps()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ορίζει τα FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.
type: docs
weight: 66
url: /el/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) μέθοδος


Ορίζει τα FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Δείτε επίσης

* Κλάση [IGifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)