---
title: get_TransitionFps()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τα FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.
type: docs
weight: 53
url: /el/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() μέθοδος

Λαμβάνει τα FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Σχόλια



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Δείτε επίσης

* Κλάση [GifOptions](../)
* Ονομαχώρος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)