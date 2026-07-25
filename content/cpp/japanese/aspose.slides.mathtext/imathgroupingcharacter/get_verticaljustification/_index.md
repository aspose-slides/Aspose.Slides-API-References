---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ文字の垂直方向の配置。オブジェクトのベースラインに対する位置合わせを指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top に設定されていると、オブジェクトの上部がベースライン上に来ます。VerticalJustification が Bottom に設定されていると、オブジェクトの下部がベースライン上に来ます。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top"
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() メソッド

グループ文字の垂直方向の配置です。オブジェクトのベースラインに対する位置合わせを指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top に設定されていると、オブジェクトの上部がベースライン上に来ます。VerticalJustification が Bottom に設定されていると、オブジェクトの下部がベースライン上に来ます。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top。

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## 備考

例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 参照

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [IMathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)