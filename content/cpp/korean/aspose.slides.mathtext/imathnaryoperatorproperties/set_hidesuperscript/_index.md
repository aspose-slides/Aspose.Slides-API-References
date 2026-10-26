---
title: set_HideSuperscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 위 첨자 숨기기
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesuperscript/
---
## IMathNaryOperatorProperties::set_HideSuperscript(bool) 메서드


위 첨자 숨기기

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSuperscript(bool value)=0
```

## 비고


예:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 관련 항목

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)