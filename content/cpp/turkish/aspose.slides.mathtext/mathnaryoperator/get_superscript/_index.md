---
title: get_Superscript()
second_title: Aspose.Slides for C++ API Referansı
description: Üst karakter argümanını belirtir; örneğin, bir integral durumunda üst sınırı ayarlar
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metot


Üst karakter argümanını belirtir; örneğin, bir integral durumunda üst sınırı ayarlar

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Açıklamalar


Örnek:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathNaryOperator](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)