---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제한(아래첨자 및 위첨자)의 위치
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) 메서드


제한(아래첨자 및 위첨자)의 위치

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## 비고


예제: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 참조

* Enum [MathLimitLocations](../../mathlimitlocations/)
* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)