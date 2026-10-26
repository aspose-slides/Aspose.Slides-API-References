---
title: set_TileFlip()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Tulis Slides::TileFlip."
type: docs
weight: 417
url: /id/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metode

Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Tulis [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Catatan

Default adalah [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Membalik ubin tekstur di sekitar sumbu vertikal.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Lihat Juga

* Enum [TileFlip](../../tileflip/)
* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)