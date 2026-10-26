---
title: get_Base()
second_title: Aspose.Slides dla C++ odwołanie API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metoda

Argument bazowy

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)