---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ文字の垂直方向の配置。ベースラインに対するオブジェクトの位置合わせを指定します。例えば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top に設定されていると、オブジェクトの上部がベースライン上に位置することを意味します；VerticalJustification が Bottom に設定されていると、オブジェクトの下部がベースライン上に位置します。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top"
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) メソッド


グループ文字の垂直方向の配置です。ベースラインに対するオブジェクトの位置合わせを指定します。例として、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top に設定されていると、オブジェクトの上部がベースラインに位置することを意味します。VerticalJustification が Bottom に設定されていると、オブジェクトの下部がベースライン上に位置します。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top です。

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
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
* ライブラリ [Aspose.Slides](../../../)