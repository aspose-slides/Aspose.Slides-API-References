---
title: set_EmbedImages()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur opsi penyematan gambar. Tulis bool.
type: docs
weight: 66
url: /id/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metode


Mengatur opsi penyematan gambar. Tulis **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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
* Pustaka [Aspose.Slides](../../../)