---
title: get_Numerator()
second_title: Riferimento API Aspose.Slides per C++
description: Numeratore
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() metodo


Numeratore

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## Osservazioni


Esempio: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFraction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)