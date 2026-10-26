---
title: set_TileOffsetX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur offset horizontal tekstur dari asal bentuk dalam satuan poin. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Tulis float.
type: docs
weight: 287
url: /id/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metode


Mengatur offset horizontal tekstur dari asal bentuk dalam satuan poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Tulis **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset horizontal tekstur menjadi 20 poin
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)