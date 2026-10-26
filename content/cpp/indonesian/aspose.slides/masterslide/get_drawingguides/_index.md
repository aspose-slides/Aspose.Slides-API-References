---
title: get_DrawingGuides()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan koleksi panduan gambar untuk master slide. Hanya-baca IDrawingGuidesCollection
type: docs
weight: 170
url: /id/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() method


Mengembalikan koleksi panduan gambar untuk master slide. Hanya-baca [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Menambahkan panduan gambar vertikal baru ke kanan pusat slide
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Kelas [MasterSlide](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)