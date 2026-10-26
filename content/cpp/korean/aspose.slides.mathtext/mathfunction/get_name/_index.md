---
title: get_Name()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 함수 이름 예를 들어, 함수 이름은 sin 및 cos입니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() 메서드


함수 이름 예를 들어, 함수 이름은 sin 및 cos입니다

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## 비고


예: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFunction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)