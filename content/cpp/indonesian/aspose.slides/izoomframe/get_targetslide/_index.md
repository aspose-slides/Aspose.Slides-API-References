---
title: get_TargetSlide()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan objek slide yang ditautkan oleh objek Slide Zoom. Baca ISlide.
type: docs
weight: 1
url: /id/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() metode

Mendapatkan objek slide yang ditautkan oleh objek [Slide](../../slide/) Zoom. Baca [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Remarks

Contoh berikut menunjukkan cara mengubah slide target dan membuat gambar baru untuk objek [Slide](../../slide/) Zoom:

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [IZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)