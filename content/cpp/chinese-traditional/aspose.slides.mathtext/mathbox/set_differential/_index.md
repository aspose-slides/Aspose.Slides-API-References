---
title: set_Differential()
second_title: Aspose.Slides for C++ API 參考
description: "Differential 為 true 時，盒子會作為微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被積分式中），並獲得適當的水平間距以呈現數學微分。預設： false"
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) 方法


Differential 當為 true 時，盒子會作為一個微分 (例如，\\uD835\\uDC51\\uDC65 在被積分式中)，並獲得適當的水平間距以呈現數學微分。預設: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## 備註


範例： 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)