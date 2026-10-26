---
title: get_DrawingGuides()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi panduan gambar. Hanya-baca IDrawingGuidesCollection
type: docs
weight: 53
url: /id/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metode


Mengembalikan koleksi panduan gambar. Hanya-baca [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Catatan


Kode contoh berikut menunjukkan cara menambahkan panduan gambar baru dalam presentasi PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Menambahkan panduan gambar vertikal baru di sebelah kanan pusat slide
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Menambahkan panduan gambar horizontal baru di bawah pusat slide
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Kelas [ICommonSlideViewProperties](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)