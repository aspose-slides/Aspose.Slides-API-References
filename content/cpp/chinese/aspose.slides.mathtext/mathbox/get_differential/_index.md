---
title: get_Differential()
second_title: Aspose.Slides for C++ API 参考
description: "Differential 为 true 时，框作为微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被积函数中），并获得适当的水平间距以显示数学微分。默认值：false"
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() 方法


Differential 为 true 时，框将作为微分（例如，\\uD835\\uDC51\\uDC65 在被积函数中），并获得适当的水平间距以显示数学微分。默认值：false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## 备注


示例： 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 参见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)