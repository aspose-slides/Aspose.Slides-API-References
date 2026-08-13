---
title: set_HideSubscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 첨자 숨기기
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesubscript/
---
## IMathNaryOperatorProperties::set_HideSubscript(bool) 메서드


첨자 숨기기

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSubscript(bool value)=0
```

## 비고


예시: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 참조

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)