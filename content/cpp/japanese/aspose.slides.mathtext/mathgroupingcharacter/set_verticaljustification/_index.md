---
title: set_VerticalJustification()
second_title: Aspose.Slides の C++ API リファレンス
description: "グループ文字の垂直揃えです。ベースラインに対するオブジェクトの配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification の Top はオブジェクトの上端がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下端がベースライン上にあります。デフォルト: Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) メソッド

グループ文字の垂直揃えです。ベースラインに対するオブジェクトの配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、Top の VerticalJustification はオブジェクトの上端がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下端がベースライン上にあります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)