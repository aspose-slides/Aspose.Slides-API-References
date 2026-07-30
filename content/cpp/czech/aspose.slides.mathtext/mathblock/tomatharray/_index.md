---
title: ToMathArray()
second_title: Aspose.Slides pro C++ API Referenci
description: Ukládá podřízené prvky do vertikálního pole
type: docs
weight: 235
url: /cs/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metoda


Ukládá podřízené prvky do vertikálního pole

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Návratová hodnota

Nová instance typu [IMathArray](../../imatharray/)
## Poznámky



Příklad: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathArray](../../imatharray/)
* Třída [MathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)