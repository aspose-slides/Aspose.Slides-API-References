---
title: get_Differential()
second_title: Aspose.Slides for C++ API リファレンス
description: "Differential が true の場合、ボックスは微分として機能します (例、\\uD835\\uDC51\\uD835\\uDC65 が積分子内にある場合)、そして数学的微分のための適切な水平間隔を受け取ります。 デフォルト: false"
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() method

Differential が true の場合、ボックスは微分として機能し (例、\\uD835\\uDC51\\uD835\\uDC65 が積分子内にある場合など)、数学的微分のために適切な水平間隔を受け取ります。 デフォルト: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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