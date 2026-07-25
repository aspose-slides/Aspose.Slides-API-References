---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "Explicit break は、Box オブジェクトの先頭に改行があるかどうかを指定し、行が Box オブジェクトの先頭で折り返されるようにします。前の行の数式テキスト内の演算子の番号を指定し、現在の行の数式テキストの配置基準点として使用されます。可能な値: 1..255 デフォルト: 0 (明示的な改行なし)"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) メソッド

Explicit break は、Box オブジェクトの先頭に改行があるかどうかを指定し、行が Box オブジェクトの先頭で折り返されるようにします。 前の行の数式テキスト内の演算子の番号を指定し、現在の行の数式テキストの配置ポイントとして使用されます。 可能な値: 1..255 デフォルト: 0 (明示的な改行なし)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 参考

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)