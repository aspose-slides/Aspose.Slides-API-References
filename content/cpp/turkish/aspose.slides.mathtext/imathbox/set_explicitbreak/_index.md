---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API Referansı
description: "Açık kesme, Box nesnesinin başında bir satır sonu olup olmadığını belirler; böylece satır Box nesnesinin başında kayar. Önceki matematiksel metin satırındaki operatörün numarasını belirler; bu numara, mevcut matematiksel metin satırının hizalama noktası olarak kullanılacaktır. Olası değerler: 1..255 Varsayılan: 0 (açık kesme yok)"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metodu

Açık kesme, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır Box nesnesinin başlangıcında kayar. Bir önceki matematiksel metin satırındaki operatörün numarasını belirtir; bu operatör, mevcut matematiksel metin satırının hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (açık kesme yok)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## İlgili

* Sınıf [IMathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)