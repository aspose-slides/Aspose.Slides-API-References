---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() metoda

Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Poznámky

Příklad:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBorderBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)