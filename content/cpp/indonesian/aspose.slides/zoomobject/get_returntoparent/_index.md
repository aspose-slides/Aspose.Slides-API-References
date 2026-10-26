---
title: get_ReturnToParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan perilaku navigasi dalam slideshow. Baca bool. Nilai default: false"
type: docs
weight: 27
url: /id/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metode

Mendapatkan perilaku navigasi dalam slideshow. Baca **bool**. Nilai default: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Catatan

Nilai true dari properti menentukan perilaku kembali ke induk dalam slideshow. 

Contoh: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lihat Juga

* Kelas [ZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)