---
title: set_AnimateTransitions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur opsi animasi transisi. Tulis bool.
type: docs
weight: 14
url: /id/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) metode


Mengatur opsi animasi transisi. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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
* Perpustakaan [Aspose.Slides](../../../)