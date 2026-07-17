---
title: get_FractionType()
second_title: Aspose.Slides for C++ API 参考
description: "分数类型 默认: Bar"
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathfraction/get_fractiontype/
---
## MathFraction::get_FractionType() 方法


分数类型 默认: Bar

```cpp
MathFractionTypes Aspose::Slides::MathText::MathFraction::get_FractionType() override
```

## 备注


示例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另见

* 枚举 [MathFractionTypes](../../mathfractiontypes/)
* 类 [MathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)