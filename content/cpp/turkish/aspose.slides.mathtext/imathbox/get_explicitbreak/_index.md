---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API Referansı
description: "Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başlangıcında kayar. Matematiksel metnin önceki satırındaki operatörün sayısını belirtir; bu sayı, mevcut matematiksel metin satırı için hizalama noktası olarak kullanılacaktır. olası değerler: 1..255 Varsayılan: 0 (no explicit break)"
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metodu

Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır, kutu nesnesinin başlangıcında kayar. Matematiksel metnin önceki satırındaki operatörün sayısını belirtir; bu sayı, mevcut matematiksel metin satırı için hizalama noktası olarak kullanılır. olası değerler: 1..255 Varsayılan: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Açıklamalar

Örnek:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## İlgili

* Sınıf [IMathBox](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)