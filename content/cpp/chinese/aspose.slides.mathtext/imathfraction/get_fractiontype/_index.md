---
title: get_FractionType()
second_title: Aspose.Slides C++ API 参考
description: "分数类型 默认: Bar"
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathfraction/get_fractiontype/
---
## IMathFraction::get_FractionType() 方法

分数类型 默认： Bar

```cpp
virtual MathFractionTypes Aspose::Slides::MathText::IMathFraction::get_FractionType()=0
```

## 备注

示例：
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另见

* 枚举 [MathFractionTypes](../../mathfractiontypes/)
* 类 [IMathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)