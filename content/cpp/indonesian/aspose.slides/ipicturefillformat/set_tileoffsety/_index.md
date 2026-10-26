---
title: set_TileOffsetY()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif menggerakkan tekstur ke bawah, sedangkan nilai negatif menggerakkannya ke atas. Tulis float.
type: docs
weight: 313
url: /id/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) metode


Mengatur offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif menggeser tekstur ke bawah, sedangkan nilai negatif menggeser ke atas. Tulis **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan format isi gambar dari bentuk
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Mengatur mode isi gambar menjadi Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Mengatur offset vertikal tekstur menjadi -50 poin
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lihat Juga

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)