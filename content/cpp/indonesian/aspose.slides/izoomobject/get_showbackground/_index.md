---
title: get_ShowBackground()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca bool. Nilai default: true"
type: docs
weight: 53
url: /id/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metode

Mendapatkan nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca **bool**. Nilai default: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Catatan

Contoh ini menunjukkan cara menghapus latar belakang gambar objek Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Lihat Juga

* Kelas [IZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)