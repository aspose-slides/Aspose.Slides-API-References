---
title: set_TileScaleX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur skala horizontal untuk pengisian tekstur sebagai persentase. Tulis float.
type: docs
weight: 339
url: /id/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) metode


Mengatur skala horizontal untuk pengisian tekstur sebagai persentase. Tulis **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Keterangan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala horizontal untuk tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)