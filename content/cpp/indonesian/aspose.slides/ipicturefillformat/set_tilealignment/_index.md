---
title: set_TileAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan bagaimana tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Tulis RectangleAlignment.
type: docs
weight: 391
url: /id/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) metode


Menetapkan bagaimana tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Tulis [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Catatan


Bawaan adalah [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format pengisian gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Menetapkan mode pengisian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Menetapkan penyelarasan ubin ke kanan bawah
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lihat Juga

* Enum [RectangleAlignment](../../rectanglealignment/)
* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)