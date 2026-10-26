---
title: get_TransitionDuration()
second_title: Aspose.Slides untuk Referensi API C++
description: "Mendapatkan durasi transisi antara Zoom dan slide. Baca float. Nilai default: 1.0f"
type: docs
weight: 105
url: /id/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() metode


Mendapatkan durasi transisi antara Zoom dan slide. Baca **float**. Nilai default: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Catatan


Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan waktu yang terkait dengan transisi tersebut. 

Contoh ini menunjukkan cara mengubah durasi transisi antara Zoom dan slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lihat Juga

* Kelas [ZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)