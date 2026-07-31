---
title: get_TileOffsetY()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sedangkan nilai negatif memindahkannya ke atas. Baca float.
type: docs
weight: 300
url: /id/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() metode


Mengembalikan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sedangkan nilai negatif memindahkannya ke atas. Baca **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format pengisian gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode pengisian gambar ke Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset vertikal tekstur ke -50 poin
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lihat Juga

* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)