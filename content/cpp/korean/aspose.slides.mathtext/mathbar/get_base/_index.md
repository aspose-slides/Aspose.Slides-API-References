---
title: get_Base()
second_title: Aspose.Slides for C++ API 참조
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() 메서드

Base 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## 비고

예제: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBar](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)