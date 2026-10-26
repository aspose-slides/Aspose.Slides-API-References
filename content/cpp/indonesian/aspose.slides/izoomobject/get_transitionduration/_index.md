---
title: get_TransitionDuration()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan durasi transisi antara Zoom dan slide. Baca float. Nilai default: 1.0f"
type: docs
weight: 105
url: /id/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metode

Mendapatkan durasi transisi antara Zoom dan slide. Baca **float**. Nilai default: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Catatan

Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan timing yang terkait dengan transisi tersebut.

contoh ini menunjukkan cara mengubah durasi transisi antara Zoom dan slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lihat Juga

* Kelas [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)