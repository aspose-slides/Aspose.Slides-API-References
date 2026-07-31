---
title: get_AnimateShapes()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan opsi animasi bentuk. Baca **bool**.
type: docs
weight: 27
url: /id/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() metode


Mengembalikan opsi animasi bentuk. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Keterangan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Lihat Juga

* Kelas [IHtml5Options](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)