---
title: get_Base()
second_title: Aspose.Slides pro C++ API Reference
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metoda

Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Poznámky

Příklad:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)