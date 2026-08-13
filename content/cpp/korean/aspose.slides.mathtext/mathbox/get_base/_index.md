---
title: get_Base()
second_title: Aspose.Slides for C++ API 참조
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() 메서드


Base 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## 비고


예제:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)