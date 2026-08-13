---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API 참조
description: 제한(아래첨자 및 위첨자)의 위치
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) 메서드

제한(아래첨자 및 위첨자)의 위치

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## 비고

예제:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 참고

* Enum [MathLimitLocations](../../mathlimitlocations/)
* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)