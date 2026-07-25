---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API リファレンス
description: "true の場合、このオペレータエミュレータは配置ポイントとして機能します。つまり、他の式で指定された配置ポイントとそれを合わせることができます。デフォルト: false"
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) メソッド


true の場合、このオペレータエミュレータは配置ポイントとして機能します。つまり、他の式で指定された配置ポイントとそれを合わせることができます。デフォルト: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
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