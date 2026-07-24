---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Funktionsname Zum Beispiel sind Funktionsnamen sin und cos
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() Methode

Funktionsname Zum Beispiel sind Funktionsnamen sin und cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Hinweise


Beispiel: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFunction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)