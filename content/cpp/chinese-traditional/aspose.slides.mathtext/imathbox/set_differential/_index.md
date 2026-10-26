---
title: set_Differential()
second_title: Aspose.Slides for C++ API 參考文件
description: "微分。當為 true 時，該方框作為微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被積函數中），並獲得適當的水平間距以符合數學微分。預設： false"
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) 方法


微分。當為 true 時，該方框作為微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被積函數中），並獲得適當的水平間距以符合數學微分。預設： false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## 備註


範例： 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 參見

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)