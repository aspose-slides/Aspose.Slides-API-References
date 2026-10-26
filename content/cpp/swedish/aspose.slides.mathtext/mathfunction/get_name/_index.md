---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Funktionsnamn Till exempel är funktionsnamn sin och cos
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metod

Funktionsnamn Till exempel är funktionsnamn sin och cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Anmärkningar


Exempel:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathFunction](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)