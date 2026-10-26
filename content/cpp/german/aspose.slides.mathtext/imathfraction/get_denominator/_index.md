---
title: get_Denominator()
second_title: Aspose.Slides für C++ API-Referenz
description: Nenner
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() Methode

Nenner

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Bemerkungen


Beispiel: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFraction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)