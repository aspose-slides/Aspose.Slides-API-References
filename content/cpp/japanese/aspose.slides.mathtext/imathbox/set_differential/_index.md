---
title: set_Differential()
second_title: Aspose.Slides for C++ API リファレンス
description: "微分。true の場合、ボックスは微分子として機能し（例：\\uD835\\uDC51\\uD835\\uDC65 を積分子に含む場合など）、数学的微分に適した水平間隔が適用されます。デフォルト: false"
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) メソッド

微分。true の場合、ボックスは微分子として機能し（例：\\uD835\\uDC51\\uD835\\uDC65 を積分子に含む場合など）、数学的微分に適した水平間隔が適用されます。デフォルト: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## 備考


例:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 参照

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)