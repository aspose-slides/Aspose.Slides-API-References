---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列要素間の垂直間隔の種類 デフォルト: SingleLineGap"
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/matharray/get_rowspacingrule/
---
## MathArray::get_RowSpacingRule() メソッド

配列要素間の垂直間隔の種類 デフォルト: SingleLineGap

```cpp
MathRowSpacingRule Aspose::Slides::MathText::MathArray::get_RowSpacingRule() override
```

## 備考

例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 参照

* 列挙型 [MathRowSpacingRule](../../mathrowspacingrule/)
* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)