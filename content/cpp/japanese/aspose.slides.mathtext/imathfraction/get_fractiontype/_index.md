---
title: get_FractionType()
second_title: Aspose.Slides for C++ API リファレンス
description: "分数タイプ デフォルト: Bar"
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathfraction/get_fractiontype/
---
## IMathFraction::get_FractionType() メソッド

分数タイプ デフォルト: Bar

```cpp
virtual MathFractionTypes Aspose::Slides::MathText::IMathFraction::get_FractionType()=0
```

## 備考

例:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 参照

* 列挙体 [MathFractionTypes](../../mathfractiontypes/)
* クラス [IMathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)