---
title: set_TileOffsetX()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan offset horizontal tekstur relatif terhadap asal bentuk dalam satuan poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Tulis float.
type: docs
weight: 287
url: /id/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) metode


Menetapkan offset horizontal tekstur relatif terhadap asal bentuk dalam satuan poin. Nilai positif memindahkan tekstur ke kanan, sedangkan nilai negatif memindahkannya ke kiri. Tulis **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
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

* Kelas [IPictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)