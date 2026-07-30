---
title: get_Denominator()
second_title: Riferimento API di Aspose.Slides per C++
description: Denominatore
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() method


Denominatore

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Osservazioni


Esempio: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFraction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)