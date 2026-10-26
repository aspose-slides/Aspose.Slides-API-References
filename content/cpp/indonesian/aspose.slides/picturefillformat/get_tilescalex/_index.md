---
title: get_TileScaleX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca float.
type: docs
weight: 326
url: /id/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metode


Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Catatan


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala horizontal untuk tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)