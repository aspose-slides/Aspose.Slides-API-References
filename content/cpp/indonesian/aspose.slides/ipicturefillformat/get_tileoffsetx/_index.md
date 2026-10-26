---
title: get_TileOffsetX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan offset horizontal tekstur dari asal bentuk dalam satuan point. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Baca float.
type: docs
weight: 274
url: /id/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() metode

Mengembalikan offset horizontal tekstur dari asal bentuk dalam satuan point. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Baca **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset horizontal tekstur menjadi 20 poin
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lihat Juga

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)