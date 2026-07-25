---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列要素間の垂直方向の間隔のタイプ
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() メソッド

配列要素間の垂直方向の間隔のタイプ

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## 備考

例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 参照

* 列挙体 [MathRowSpacingRule](../../mathrowspacingrule/)
* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)