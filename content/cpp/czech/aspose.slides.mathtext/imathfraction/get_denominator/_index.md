---
title: get_Denominator()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Jmenovatel
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() metoda


Jmenovatel

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Poznámky


Příklad: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathFraction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)