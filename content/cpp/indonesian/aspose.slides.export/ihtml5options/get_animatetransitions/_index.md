---
title: get_AnimateTransitions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan opsi animasi transisi. Baca bool.
type: docs
weight: 1
url: /id/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() metode


Mengembalikan opsi animasi transisi. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Catatan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Lihat Juga

* Kelas [IHtml5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)