---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Base argument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() metod


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Anmärkningar


Exempel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathBar](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)