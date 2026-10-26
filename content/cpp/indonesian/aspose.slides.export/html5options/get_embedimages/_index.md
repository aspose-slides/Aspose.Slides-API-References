---
title: get_EmbedImages()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan opsi penyematan gambar. Baca bool.
type: docs
weight: 53
url: /id/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metode


Mengembalikan opsi penyematan gambar. Baca **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Lihat Juga

* Kelas [Html5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)