---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Base argument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metod

Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Anmärkningar

Exempel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IMathElement](../../imathelement/)
* klass [MathBox](../)
* namnrymd [Aspose::Slides::MathText](../../)
* bibliotek [Aspose.Slides](../../../)