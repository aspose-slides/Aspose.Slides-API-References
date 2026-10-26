---
title: set_TransitionFps()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur FPS transisi [frames/sec] Nilai default adalah 25.
type: docs
weight: 66
url: /id/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) metode


Mengatur FPS transisi [frames/sec] Nilai default adalah 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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
* Perpustakaan [Aspose.Slides](../../../)