---
title: get_TileFlip()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Baca Slides::TileFlip."
type: docs
weight: 404
url: /id/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metode


Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Baca [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Catatan


Default adalah [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Membalik ubin tekstur di sekitar sumbu vertikal.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Lihat Juga

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)