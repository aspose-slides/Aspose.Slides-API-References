---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Funktionsnamn Till exempel är funktionsnamn sin och cos
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() metod


Funktionsnamn Till exempel är funktionsnamn sin och cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Anmärkningar


Exempel: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathFunction](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)