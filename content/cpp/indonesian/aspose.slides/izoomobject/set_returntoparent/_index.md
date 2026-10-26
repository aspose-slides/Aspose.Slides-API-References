---
title: set_ReturnToParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur perilaku navigasi dalam tampilan slide. Tulis bool. Nilai default: false"
type: docs
weight: 40
url: /id/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metode

Mengatur perilaku navigasi dalam tampilan slide. Tulis **bool**. Nilai default: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Catatan

Nilai true properti menentukan perilaku kembali ke induk dalam navigasi tampilan slide. 

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