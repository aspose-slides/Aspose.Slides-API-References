---
title: set_TileOffsetY()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif menggerakkan tekstur ke bawah, sementara nilai negatif menggerakkannya ke atas. Tulis float.
type: docs
weight: 313
url: /id/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metode

Mengatur offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif menggerakkan tekstur ke bawah, sementara nilai negatif menggerakkannya ke atas. Tulis **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset vertikal tekstur menjadi -50 poin
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)