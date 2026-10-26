---
title: set_FractionType()
second_title: Aspose.Slides for C++ API 參考文件
description: "分數類型 預設: Bar"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathfraction/set_fractiontype/
---
## MathFraction::set_FractionType(MathFractionTypes) 方法

分數類型 預設： Bar

```cpp
void Aspose::Slides::MathText::MathFraction::set_FractionType(MathFractionTypes value) override
```

## 備註

範例： 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 另請參閱

* 列舉 [MathFractionTypes](../../mathfractiontypes/)
* 類別 [MathFraction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)