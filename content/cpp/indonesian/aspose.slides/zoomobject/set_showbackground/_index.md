---
title: set_ShowBackground()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Tulis bool. Nilai default: true"
type: docs
weight: 66
url: /id/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) metode


Mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Tulis **bool**. Nilai default: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Keterangan


contoh ini menunjukkan penghapusan latar belakang gambar dari objek Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Lihat Juga

* Kelas [ZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)