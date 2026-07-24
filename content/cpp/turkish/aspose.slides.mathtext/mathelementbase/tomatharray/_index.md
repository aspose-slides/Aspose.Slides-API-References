---
title: ToMathArray()
second_title: Aspose.Slides for C++ API Referansı
description: Dikey bir diziye yerleştirir
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metod


Dikey bir diziye yerleştirir

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Dönüş Değeri

Yeni [IMathArray](../../imatharray/) tipinde bir örnek
## Açıklamalar



Örnek: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathArray](../../imatharray/)
* Sınıf [MathElementBase](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)