---
title: get_TileAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan cara tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Baca RectangleAlignment.
type: docs
weight: 378
url: /id/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metode

Mengembalikan cara tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Baca [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Catatan

Nilai default adalah [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur perataan tile ke kanan bawah
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lihat Juga

* Enum [RectangleAlignment](../../rectanglealignment/)
* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)