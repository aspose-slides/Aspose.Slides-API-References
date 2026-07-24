---
title: set_LimitLocation()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Ort der Grenzen (Tiefstellung und Hochstellung)
type: docs
weight: 79
url: /de/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) Methode


Der Ort der Grenzen (Tiefstellung und Hochstellung)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Anmerkungen


Beispiel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Siehe auch

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)