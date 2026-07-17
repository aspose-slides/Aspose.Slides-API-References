---
title: set_FractionType()
second_title: Aspose.Slides C++ API 参考
description: "分数类型 默认: Bar"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathfraction/set_fractiontype/
---
## IMathFraction::set_FractionType(MathFractionTypes) method


分数类型 默认：Bar

```cpp
virtual void Aspose::Slides::MathText::IMathFraction::set_FractionType(MathFractionTypes value)=0
```

## 备注


示例:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另请参见

* 枚举 [MathFractionTypes](../../mathfractiontypes/)
* 类 [IMathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)