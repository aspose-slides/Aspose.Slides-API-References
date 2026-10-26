---
title: set_Differential()
second_title: Aspose.Slides C++ API 参考
description: "微分。当为 true 时，盒子充当微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被积函数中），并获得适用于数学微分的适当水平间距。默认值： false"
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) 方法


微分。当为 true 时，盒子充当微分（例如，\\uD835\\uDC51\\uDC65 在被积函数中），并获得适用于数学微分的适当水平间距。默认值： false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## 备注


示例： 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 另请参阅

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)