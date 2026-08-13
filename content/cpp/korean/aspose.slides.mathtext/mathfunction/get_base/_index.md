---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 함수 인수
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() 메서드


함수 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## 비고


예시:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFunction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)