---
title: get_Superscript()
second_title: Aspose.Slides C++ için API Referansı
description: Bir üstsimge argümanını belirtir; örneğin, bir integral durumunda üst sınırı ayarlar.
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() metodu

Bir üst simge argümanını belirtir; örneğin, bir integral durumunda üst sınırı ayarlar.

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Açıklamalar

Örnek:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathNaryOperator](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)