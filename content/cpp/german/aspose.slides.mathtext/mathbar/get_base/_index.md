---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Base-Argument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() Methode


Base Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Hinweise


Beispiel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBar](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)