---
title: set_FractionType()
second_title: Aspose.Slides C++ API 參考
description: "分數類型 預設：Bar"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathfraction/set_fractiontype/
---
## IMathFraction::set_FractionType(MathFractionTypes) 方法

Fraction type 預設：Bar

```cpp
virtual void Aspose::Slides::MathText::IMathFraction::set_FractionType(MathFractionTypes value)=0
```

## 備註

範例：
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另請參閱

* Enum [MathFractionTypes](../../mathfractiontypes/)
* 類別 [IMathFraction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)