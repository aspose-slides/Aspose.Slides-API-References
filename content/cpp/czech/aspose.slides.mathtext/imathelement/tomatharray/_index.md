---
title: ToMathArray()
second_title: Aspose.Slides pro C++ – reference API
description: Vkládá do vertikálního pole
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metoda

Vkládá do vertikálního pole

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### Návratová hodnota

Nová instance typu [IMathArray](../../imatharray/)
## Poznámky



Příklad: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathArray](../../imatharray/)
* Třída [IMathElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)