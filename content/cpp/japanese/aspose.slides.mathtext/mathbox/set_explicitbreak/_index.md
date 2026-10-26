---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "Explicit break は、Box オブジェクトの開始位置に改行があるかどうかを指定し、行が Box オブジェクトの開始位置で折り返されるようにします。 前の数式テキスト行の演算子番号を指定し、現在の数式テキスト行の配置ポイントとして使用されます。可能な値: 1..255 デフォルト: 0 (明示的な改行なし)"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) メソッド


Explicit break は、Box オブジェクトの開始位置に改行があるかどうかを指定し、行が Box オブジェクトの開始位置で折り返されるようにします。 前の数式テキスト行の演算子の番号を指定し、現在の数式テキスト行の配置ポイントとして使用されます。可能な値: 1..255 デフォルト: 0 (no explicit break)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## 備考


例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 参照

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)