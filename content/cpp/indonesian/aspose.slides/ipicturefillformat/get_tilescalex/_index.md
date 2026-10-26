---
title: get_TileScaleX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca float.
type: docs
weight: 326
url: /id/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() method

Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Keterangan

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format pengisian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode pengisian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala horizontal untuk tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lihat Juga

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)