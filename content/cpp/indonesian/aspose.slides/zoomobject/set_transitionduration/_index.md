---
title: set_TransitionDuration()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur durasi transisi antara Zoom dan slide. Tulis float. Nilai default: 1.0f"
type: docs
weight: 118
url: /id/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metode

Mengatur durasi transisi antara Zoom dan slide. Tulis **float**. Nilai default: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Catatan

Jika tidak ditentukan (TransitionDur = 0), maka akan menggunakan transisi slide tujuan dan waktu yang terkait dengan transisi tersebut.

contoh menunjukkan cara mengubah durasi transisi antara Zoom dan slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lihat Juga

* Kelas [ZoomObject](../)
* RuangNama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)