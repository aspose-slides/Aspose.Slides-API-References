---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() metod

Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Anmärkningar

Exempel:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBorderBox](../)
* Namnutrymme [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)