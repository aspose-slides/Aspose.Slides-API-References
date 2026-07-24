---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Funktionsname Zum Beispiel, Funktionsnamen sind sin und cos
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() Methode

Funktionsname Zum Beispiel, Funktionsnamen sind sin und cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Anmerkungen

Beispiel:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)