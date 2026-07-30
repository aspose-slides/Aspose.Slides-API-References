---
title: get_Numerator()
second_title: Riferimento API di Aspose.Slides per C++
description: Numeratore
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() metodo


Numerator

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## Note


Esempio: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)