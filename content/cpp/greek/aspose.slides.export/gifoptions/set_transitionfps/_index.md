---
title: set_TransitionFps()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.
type: docs
weight: 66
url: /el/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) μέθοδος

Ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Δείτε επίσης

* Κλάση [GifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)