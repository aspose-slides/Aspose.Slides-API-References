---
title: ToMathArray()
second_title: Aspose.Slides for C++ API Referansı
description: Alt öğeleri dikey bir diziye koyar
type: docs
weight: 235
url: /tr/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metodu

Alt öğeleri dikey bir diziye koyar

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### Dönüş Değeri

Yeni bir [IMathArray](../../imatharray/) türünden örnek

## Açıklamalar

Örnek:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathArray](../../imatharray/)
* Sınıf [MathBlock](../)
* Adalanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)