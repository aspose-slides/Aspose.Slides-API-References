---
title: set_Differential()
second_title: Aspose.Slides for C++ API リファレンス
description: "Differential が true の場合、ボックスは微分として機能し（例: \\uD835\\uDC51\\uD835\\uDC65 を積分子に使用）、数学的微分に対して適切な水平間隔を受け取ります。デフォルト: false"
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) メソッド


Differential true の場合、ボックスは微分として機能し（例: \\uD835\\uDC51\\uD835\\uDC65 を積分子に含む）、数学的微分に適した水平間隔を受け取ります。デフォルト: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)