---
title: get_TileOffsetY()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan offset vertikal tekstur dari asal bentuk dalam satuan point. Nilai positif menggerakkan tekstur ke bawah, sementara nilai negatif menggerakkannya ke atas. Baca float.
type: docs
weight: 300
url: /id/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metode

Mengembalikan offset vertikal tekstur dari asal bentuk dalam satuan point. Nilai positif menggerakkan tekstur ke bawah, sementara nilai negatif menggerakkannya ke atas. Baca **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isian gambar dari shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isian gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset vertikal tekstur menjadi -50 poin
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lihat Juga

* Kelas [IPictureFillFormat](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)