---
title: get_Limit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제한 인수
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() 메서드


제한 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## 비고


예: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathLimit](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)