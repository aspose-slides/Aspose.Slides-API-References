---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Funktionsargument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metod

Funktionsargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
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
* Klass [IMathFunction](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)