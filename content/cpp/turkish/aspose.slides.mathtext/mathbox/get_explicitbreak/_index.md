---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API Referansı
description: "Açık kesme, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler, böylece satır Box nesnesinin başlangıcında kayar. Önceki satırdaki matematiksel metnin operatör sayısını belirtir; bu sayı, geçerli satırdaki matematiksel metnin hizalama noktası olarak kullanılacaktır. olası değerler: 1..255 Varsayılan: 0 (açık kesme yok)"
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metot

Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir, böylece satır Box nesnesinin başlangıcında kayar. Önceki satırdaki matematiksel metnin operatör sayısını belirler; bu sayı, geçerli satırdaki matematiksel metnin hizalama noktası olarak kullanılacaktır. olası değerler: 1..255 Varsayılan: 0 (no explicit break)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Açıklamalar


Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Ayrıca Bakınız

* Sınıf [MathBox](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)