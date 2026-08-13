---
title: get_HideSubscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 아래 첨자 숨기기
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() 메서드

아래 첨자 숨기기

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## 비고

예제: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 참조

* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)