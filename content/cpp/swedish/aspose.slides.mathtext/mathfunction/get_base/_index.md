---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Funktionsargument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metod


Funktionsargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Anmärkningar


Exempel:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathFunction](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)