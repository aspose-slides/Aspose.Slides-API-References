---
title: get_TileAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan cara tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Baca RectangleAlignment.
type: docs
weight: 378
url: /id/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metode


Mengembalikan bagaimana tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Baca [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Catatan


Nilai default adalah [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format pengisian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode pengisian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur perataan ubin ke kanan bawah
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lihat Juga

* Enum [RectangleAlignment](../../rectanglealignment/)
* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)