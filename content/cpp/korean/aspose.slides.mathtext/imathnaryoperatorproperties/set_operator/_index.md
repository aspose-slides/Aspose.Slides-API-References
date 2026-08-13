---
title: set_Operator()
second_title: Aspose.Slides for C++ API 참조
description: "다항 연산자 문자 예: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) 메서드

다항 연산자 문자 예: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## 비고

예: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 관련 항목

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)