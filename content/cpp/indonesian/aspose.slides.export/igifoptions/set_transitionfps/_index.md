---
title: set_TransitionFps()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur FPS transisi [frame/detik] Nilai default adalah 25.
type: docs
weight: 66
url: /id/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) metode


Mengatur FPS transisi [frame/detik] Nilai default adalah 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Catatan


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lihat Juga

* Kelas [IGifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)