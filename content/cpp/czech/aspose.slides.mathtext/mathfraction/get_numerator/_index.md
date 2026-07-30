---
title: get_Numerator()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Čitatel
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() metoda


Čitatel

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## Poznámky


Příklad: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathFraction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)