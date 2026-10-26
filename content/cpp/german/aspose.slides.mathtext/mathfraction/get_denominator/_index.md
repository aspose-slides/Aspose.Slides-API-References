---
title: get_Denominator()
second_title: Aspose.Slides für C++ API Referenz
description: Nenner
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() Methode


Nenner

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## Anmerkungen


Beispiel: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFraction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)