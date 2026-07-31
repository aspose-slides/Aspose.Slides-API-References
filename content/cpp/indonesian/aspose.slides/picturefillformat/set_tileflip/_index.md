---
title: set_TileFlip()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Tulis Slides::TileFlip."
type: docs
weight: 417
url: /id/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metode


Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Tulis [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Catatan


Bawaan adalah [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Membalik ubin tekstur di sekitar sumbu vertikal.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Lihat Juga

* Enum [TileFlip](../../tileflip/)
* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)