---
title: set_FractionType()
second_title: Aspose.Slides C++ API 参考
description: "分数类型 默认: Bar"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathfraction/set_fractiontype/
---
## MathFraction::set_FractionType(MathFractionTypes) 方法


Fraction type Default: Bar

```cpp
void Aspose::Slides::MathText::MathFraction::set_FractionType(MathFractionTypes value) override
```

## 备注


示例:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另请参阅

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)