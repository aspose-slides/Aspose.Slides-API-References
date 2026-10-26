---
title: set_TileAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan bagaimana tekstur disejajarkan dalam bentuk. Pengaturan ini mengontrol titik mulai pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Tulis RectangleAlignment.
type: docs
weight: 391
url: /id/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) metode


Mengatur bagaimana tekstur disejajarkan dalam bentuk. Pengaturan ini mengontrol titik mulai pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Tuliskan [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Catatan


Nilai default adalah [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar ke Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur perataan ubin ke kanan bawah
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lihat Juga

* Enum [RectangleAlignment](../../rectanglealignment/)
* Kelas [PictureFillFormat](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)