---
title: get_TileOffsetX()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Baca float.
type: docs
weight: 274
url: /id/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() metode


Mengembalikan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Baca **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset horizontal tekstur menjadi 20 poin
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)