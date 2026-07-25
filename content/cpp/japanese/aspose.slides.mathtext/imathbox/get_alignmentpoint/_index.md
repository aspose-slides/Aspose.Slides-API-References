---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API リファレンス
description: "true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントをそれに合わせて整列させることができます。既定: false"
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() メソッド

true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントをそれに合わせて整列させることができます。既定: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 参照

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)