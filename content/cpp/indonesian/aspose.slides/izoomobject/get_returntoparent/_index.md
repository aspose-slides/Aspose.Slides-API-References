---
title: get_ReturnToParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengambil perilaku navigasi dalam slideshow. Baca bool. Nilai default: false"
type: docs
weight: 27
url: /id/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metode

Mengambil perilaku navigasi dalam slideshow. Baca **bool**. Nilai default: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Catatan

Nilai true dari properti menentukan perilaku kembali ke induk dalam slideshow. 

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lihat Juga

* Kelas [IZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)