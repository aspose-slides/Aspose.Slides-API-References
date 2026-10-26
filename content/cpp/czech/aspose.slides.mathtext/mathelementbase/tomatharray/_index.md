---
title: ToMathArray()
second_title: Aspose.Slides pro C++ API Reference
description: Vkládá do svislého pole
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metoda


Vkládá do vertikálního pole

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
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
* Třída [MathElementBase](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)