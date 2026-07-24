---
title: ToMathArray()
second_title: Aspose.Slides for C++ API Referansı
description: Dikey bir diziye yerleştirir
type: docs
weight: 183
url: /tr/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() method


Dikey bir diziye yerleştirir

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Dönüş Değeri

Yeni bir [IMathArray](../../imatharray/) örneği
## Açıklamalar



Örnek: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathArray](../../imatharray/)
* Sınıf [IMathElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)