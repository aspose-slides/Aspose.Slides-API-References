---
title: set_AnimateShapes()
second_title: Aspose.Slides için C++ API Referansı
description: Şekil animasyonu seçeneğini ayarlar. bool yazın.
type: docs
weight: 40
url: /tr/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) metodu


Şekil animasyonu seçeneğini ayarlar. **bool** yazın.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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