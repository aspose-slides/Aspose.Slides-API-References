---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に合わせることができます。既定値: Center"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) メソッド

配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に合わせることができます。既定値: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## 備考

例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 参照

* 列挙型 [MathVerticalAlignment](../../mathverticalalignment/)
* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)