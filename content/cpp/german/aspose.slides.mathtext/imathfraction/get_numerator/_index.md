---
title: get_Numerator()
second_title: Aspose.Slides für C++ API-Referenz
description: Zähler
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMMathFraction::get_Numerator() Methode


Zähler

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## Bemerkungen


Beispiel: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Siehe Auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFraction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)