---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API リファレンス
description: "true の場合、この演算子エミュレーターは配置点として機能します。つまり、他の式で指定された配置点をそれに合わせることができます。デフォルト: false"
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) メソッド

true の場合、この演算子エミュレータは配置点として機能します。つまり、他の式で指定された配置点をこれに合わせることができます。デフォルト: false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 参照

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)