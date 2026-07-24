---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API Referansı
description: "Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başında kayar. Matematiksel metnin önceki satırındaki operatörün sayısını belirtir; bu, mevcut matematiksel metin satırı için hizalama noktası olarak kullanılacaktır. Olası değerler: 1..255 Varsayılan: 0 (explicit break yok)"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metod


Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başında kayar. Matematiksel metnin önceki satırındaki operatörün sayısını belirtir; bu operatör, mevcut matematiksel metin satırı için hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (explicit break yok)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Açıklamalar


Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Diğer

* Sınıf [MathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)