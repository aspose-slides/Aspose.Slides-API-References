---
title: set_AnimateShapes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur opsi animasi bentuk. Tulis bool.
type: docs
weight: 40
url: /id/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) metode

Mengatur opsi animasi bentuk. Tulis **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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