---
title: get_LimitLocation()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 제한(아래첨자 및 위첨자)의 위치
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() 메서드


제한(아래첨자 및 위첨자)의 위치

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## 비고


예:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 참조

* 열거형 [MathLimitLocations](../../mathlimitlocations/)
* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)