---
title: set_Differential()
second_title: Aspose.Slides for C++ API 참조
description: "미분. true인 경우, 박스가 미분으로 작동합니다 (예: \\uD835\\uDC51\\uD835\\uDC65 in an integrand), 그리고 수학적 미분에 적합한 가로 간격을 받습니다. 기본값: false"
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) 메서드


미분. true인 경우, 박스는 미분으로 작동합니다 (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), 그리고 수학적 미분에 필요한 적절한 가로 간격을 받습니다. 기본값: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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