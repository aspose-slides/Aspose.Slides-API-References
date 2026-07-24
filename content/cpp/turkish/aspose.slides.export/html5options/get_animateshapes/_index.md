---
title: get_AnimateShapes()
second_title: Aspose.Slides için C++ API Referansı
description: Şekillerin animasyon seçeneğini döndürür. bool okunur.
type: docs
weight: 27
url: /tr/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metod

Şekillerin animasyon seçeneğini döndürür. **bool** okunur.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Açıklamalar

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## İlgili

* Sınıf [Html5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)