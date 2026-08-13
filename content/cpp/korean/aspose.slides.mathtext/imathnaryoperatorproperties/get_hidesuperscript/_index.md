---
title: get_HideSuperscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 위첨자 숨기기
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesuperscript/
---
## IMathNaryOperatorProperties::get_HideSuperscript() 메서드

위첨자 숨기기

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSuperscript()=0
```

## 비고

예제: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 참조

* 클래스 [IMathNaryOperatorProperties](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)