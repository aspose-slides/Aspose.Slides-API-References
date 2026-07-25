---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の配置を周囲のテキストに対して指定します。配列外のテキストは配列オブジェクトの下部、上部、または中央に揃えることができます。デフォルト値: Center"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() メソッド

配列の配置を周囲のテキストに対して指定します。配列外のテキストは配列オブジェクトの下部、上部、または中央に揃えることができます。デフォルト値: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## 備考

例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 参照

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)