---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() 메서드

Base 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## 비고

예시: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathLimit](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)