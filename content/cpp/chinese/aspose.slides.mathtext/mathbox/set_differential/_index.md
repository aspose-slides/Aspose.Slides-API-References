---
title: set_Differential()
second_title: Aspose.Slides for C++ API 参考
description: "当为 true 时，框作为微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被积函数中），并获得适用于数学微分的水平间距。默认值：false"
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) 方法


Differential 当为 true 时，框将作为微分（例如，\\uD835\\uDC51\\uD835\\uDC65 在被积函数中），并获得适用于数学微分的水平间距。默认值：false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## 备注


示例：
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 另见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)