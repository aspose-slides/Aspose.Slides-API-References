---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "Explicit break は、Box オブジェクトの先頭に改行があるかどうかを指定し、行が Box オブジェクトの先頭で折り返されるようにします。前の行の数式テキストにある演算子の番号を指定し、現在の行の数式テキストの配置ポイントとして使用します。可能な値: 1..255 デフォルト: 0 (明示的な改行なし)"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() メソッド

Explicit break は、Box オブジェクトの先頭に改行があるかどうかを指定し、行が Box オブジェクトの先頭で折り返されるようにします。前の行の数式テキストにある演算子の番号を指定し、現在の行の数式テキストの配置ポイントとして使用します。可能な値: 1..255 デフォルト: 0 (no explicit break)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## 備考

Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 参照

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)