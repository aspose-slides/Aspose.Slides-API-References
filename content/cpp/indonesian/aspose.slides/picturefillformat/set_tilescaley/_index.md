---
title: set_TileScaleY()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengatur skala vertikal untuk isian tekstur sebagai persentase. Tulis float.
type: docs
weight: 365
url: /id/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metode

Mengatur skala vertikal untuk isian tekstur sebagai persentase. Tulis **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala vertikal tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)