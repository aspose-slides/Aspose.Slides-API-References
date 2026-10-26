---
title: set_TargetSlide()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur objek slide yang ditautkan oleh objek Slide Zoom. Tulis ISlide.
type: docs
weight: 14
url: /id/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metode

Mengatur objek slide yang ditautkan oleh objek [Slide](../../slide/) Zoom. Tulis [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Catatan

Contoh berikut menunjukkan cara mengubah slide target dan membuat gambar baru untuk objek [Slide](../../slide/) Zoom: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [IZoomFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)