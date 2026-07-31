---
title: get_TransitionFps()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan FPS transisi [frames/sec] Nilai defaultnya adalah 25.
type: docs
weight: 53
url: /id/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metode


Mendapatkan FPS transisi [frames/sec] Nilai defaultnya adalah 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Keterangan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lihat Juga

* Kelas [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)