---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API リファレンス
description: "true の場合、このオペレーターエミュレータは整列ポイントとして機能します; つまり、他の方程式で指定された整列ポイントをそれと整列させることができます。デフォルト: false"
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() メソッド


true のとき、このオペレーターエミュレータは整列ポイントとして機能します。つまり、他の方程式で指定された整列ポイントをそれと整列させることができます。デフォルト: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
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