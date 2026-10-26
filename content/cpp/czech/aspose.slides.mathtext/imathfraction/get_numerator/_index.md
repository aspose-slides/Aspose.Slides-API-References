---
title: get_Numerator()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Čitatel
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() metoda

Čitatel

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## Poznámky

Příklad: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathFraction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)