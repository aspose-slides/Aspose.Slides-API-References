---
title: get_Operator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Nary 연산자 문자 예: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() 메서드

Nary 연산자 문자 예: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```
## 비고

예:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```
## 참고

* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)