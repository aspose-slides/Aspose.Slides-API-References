---
title: get_TileScaleY()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan skala vertikal untuk pengisian tekstur sebagai persentase. Baca float.
type: docs
weight: 352
url: /id/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metode


Mengembalikan skala vertikal untuk pengisian tekstur sebagai persentase. Baca **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala vertikal untuk tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)