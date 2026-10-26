---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API 참조
description: 연산자 문자가 피연산자의 높이에 맞게 수직으로 성장합니다
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() 메서드


연산자 문자가 피연산자의 높이에 맞게 수직으로 성장합니다

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## 비고


예시: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 관련 항목

* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)