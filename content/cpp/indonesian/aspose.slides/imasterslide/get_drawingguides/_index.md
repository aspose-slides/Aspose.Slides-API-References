---
title: get_DrawingGuides()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi panduan gambar untuk master slide. Baca-saja IDrawingGuidesCollection
type: docs
weight: 105
url: /id/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() metode

Mengembalikan koleksi panduan gambar untuk master slide. Baca-saja [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Menambahkan panduan gambar vertikal baru ke kanan tengah slide
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Kelas [IMasterSlide](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)