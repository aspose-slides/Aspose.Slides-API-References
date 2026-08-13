---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 연산자 문자는 피연산자 높이에 맞게 수직으로 확대됩니다.
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) method


연산자 문자는 피연산자 높이에 맞게 수직으로 확대됩니다.

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## 비고


예: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 또 보기

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)