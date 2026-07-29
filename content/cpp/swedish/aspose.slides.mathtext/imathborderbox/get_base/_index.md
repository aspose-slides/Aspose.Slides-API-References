---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Base argument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metod


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Anmärkningar


Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathBorderBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)