---
title: get_TileFlip()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Baca Slides::TileFlip."
type: docs
weight: 404
url: /id/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metode


Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Baca [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Keterangan


Bawaan adalah [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format pengisian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode pengisian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Membalik ubin tekstur di sekitar sumbu vertikal.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Lihat Juga

* Enum [TileFlip](../../tileflip/)
* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)