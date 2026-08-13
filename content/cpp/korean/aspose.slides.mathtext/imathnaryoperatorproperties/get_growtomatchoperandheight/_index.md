---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Operator Character가 피연산자 높이에 맞추어 수직으로 성장합니다
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() 메서드

Operator Character가 피연산자 높이에 맞추어 수직으로 성장합니다

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## 비고

Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 참조

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)