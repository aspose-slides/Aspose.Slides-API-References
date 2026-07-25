---
title: get_Differential()
second_title: Aspose.Slides for C++ API リファレンス
description: "微分。true の場合、ボックスは微分として動作し（例: \\uD835\\uDC51\\uD835\\uDC65 が積分子にある場合）、数学的微分に適した水平間隔を受け取ります。既定値: false"
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() メソッド

微分。true の場合、ボックスは微分として機能し（例: \\uD835\\uDC51\\uD835\\uDC65 が積分子にある場合）、数学的微分に適した水平間隔を受け取ります。既定値: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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