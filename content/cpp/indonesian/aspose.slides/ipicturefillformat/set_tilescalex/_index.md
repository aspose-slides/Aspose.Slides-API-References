---
title: set_TileScaleX()
second_title: Aspose.Slides untuk Referensi API C++
description: Menetapkan skala horizontal untuk isian tekstur sebagai persentase. Tulis float.
type: docs
weight: 339
url: /id/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metode


Menetapkan skala horizontal untuk isian tekstur sebagai persentase. Tulis **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)