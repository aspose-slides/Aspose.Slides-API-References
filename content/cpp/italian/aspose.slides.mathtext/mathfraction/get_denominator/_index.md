---
title: get_Denominator()
second_title: Riferimento API di Aspose.Slides per C++
description: Denominatore
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() method


Denominatore

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
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
* Classe [MathFraction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)