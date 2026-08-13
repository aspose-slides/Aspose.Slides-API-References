---
title: get_Differential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "미분. true이면, 박스가 미분으로 작동하며(예: \\uD835\\uDC51\\uD835\\uDC65가 적분식에 포함될 때), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false"
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() 메서드

미분. true이면, 박스가 미분으로 작동하며(예: \\uD835\\uDC51\\uD835\\uDC65가 적분식에 포함될 때), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## 비고

예: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 참조

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)