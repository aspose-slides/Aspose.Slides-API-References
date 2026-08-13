---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 한계(첨자와 위첨자)의 위치
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() method


한계(첨자와 위첨자)의 위치

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## 비고


예시: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 참조

* 열거형 [MathLimitLocations](../../mathlimitlocations/)
* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)