---
title: get_Base()
second_title: Aspose.Slides for C++ API 참조
description: 함수 인수
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() 메서드


함수 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## 비고


예제: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathFunction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)