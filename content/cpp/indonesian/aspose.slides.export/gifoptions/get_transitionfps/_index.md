---
title: get_TransitionFps()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan FPS transisi [frame/detik] Nilai defaultnya adalah 25.
type: docs
weight: 53
url: /id/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metode

Mendapatkan FPS transisi [frame/detik] Nilai defaultnya adalah 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Lihat Juga

* Kelas [GifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)