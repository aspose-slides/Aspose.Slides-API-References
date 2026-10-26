---
title: set_FractionType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "분수 유형 기본값: Bar"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathfraction/set_fractiontype/
---
## IMathFraction::set_FractionType(MathFractionTypes) 메서드


분수 유형 기본값: Bar

```cpp
virtual void Aspose::Slides::MathText::IMathFraction::set_FractionType(MathFractionTypes value)=0
```

## 비고


Example: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 참고

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 클래스 [IMathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)