---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の周囲のテキストに対する配置を指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。デフォルト値: Center"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() メソッド


配列の周囲のテキストに対する配置を指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。デフォルト値: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## 備考


例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 参照

* 列挙型 [MathVerticalAlignment](../../mathverticalalignment/)
* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)