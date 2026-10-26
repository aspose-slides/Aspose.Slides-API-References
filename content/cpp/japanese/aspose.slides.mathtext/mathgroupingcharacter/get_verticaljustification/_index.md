---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ文字の垂直配置。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、Top の VerticalJustification はオブジェクトの上部がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top"
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() メソッド


グループ文字の垂直配置。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、Top の VerticalJustification はオブジェクトの上部がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## 備考


例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 関連項目

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)