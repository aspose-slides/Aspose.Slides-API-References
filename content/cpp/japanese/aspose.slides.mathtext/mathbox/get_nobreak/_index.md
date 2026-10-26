---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API Reference
description: "改行なし このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。 true の場合、ボックス内で改行は発生しません。このプロパティは、2 つ以上の二項演算子からなる演算子エミュレータにとって重要です。この要素が指定されていない場合、ボックス内で改行が発生する可能性があります。 デフォルト: true"
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() メソッド

No break このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。 true の場合、ボックス内で改行は発生しません。このプロパティは、2 つ以上の二項演算子で構成される演算子エミュレータにとって重要です。この要素が指定されていない場合、ボックス内で改行が発生する可能性があります。デフォルト: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## 備考


例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 参照

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)