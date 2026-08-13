---
title: get_Base()
second_title: Aspose.Slides for C++ API 참조
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() 메서드


Base 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## 비고


예시: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)