---
title: set_TileScaleY()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan skala vertikal untuk pengisian tekstur sebagai persentase. Tulis float.
type: docs
weight: 365
url: /id/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) metode


Menetapkan skala vertikal untuk pengisian tekstur sebagai persentase. Tulis **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format picture fill dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode picture fill menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur skala vertikal untuk tekstur menjadi 120 persen
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lihat Juga

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)