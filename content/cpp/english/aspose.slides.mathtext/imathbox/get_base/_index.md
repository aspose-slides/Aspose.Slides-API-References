---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 1
url: /aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() method


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)