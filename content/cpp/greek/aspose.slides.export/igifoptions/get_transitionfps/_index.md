---
title: get_TransitionFps()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Λαμβάνει το FPS μετάβασης [frames/sec]. Η προεπιλεγμένη τιμή είναι 25.
type: docs
weight: 53
url: /el/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() μέθοδος

Λαμβάνει το FPS μετάβασης [frames/sec]. Η προεπιλεγμένη τιμή είναι 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Σχόλια



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