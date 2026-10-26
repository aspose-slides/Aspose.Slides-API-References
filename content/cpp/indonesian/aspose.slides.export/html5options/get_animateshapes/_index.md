---
title: get_AnimateShapes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan opsi animasi bentuk. Baca bool.
type: docs
weight: 27
url: /id/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metode


Mengembalikan opsi animasi bentuk. Baca **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Catatan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Lihat Juga

* Kelas [Html5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)