---
title: set_ReturnToParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur perilaku navigasi dalam slideshow. Tulis bool. Nilai default: false"
type: docs
weight: 40
url: /id/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metode


Mengatur perilaku navigasi dalam slideshow. Tulis **bool**. Nilai default: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Catatan


Nilai true dari properti menunjukkan perilaku navigasi kembali ke induk dalam slideshow. 

Contoh: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lihat Juga

* Kelas [ZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)