---
title: get_Base()
second_title: Aspose.Slides für C++ API Referenz
description: Base Argument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() Methode


Base Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
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
* Klasse [IMathBar](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)