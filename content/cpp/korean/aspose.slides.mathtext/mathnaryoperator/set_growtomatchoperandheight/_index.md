---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API 레퍼런스
description: 연산자 문자는 피연산자의 높이에 맞게 수직으로 늘어납니다.
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) method

연산자 문자는 피연산자의 높이에 맞게 수직으로 늘어납니다.

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## 비고

예:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 참고

* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)