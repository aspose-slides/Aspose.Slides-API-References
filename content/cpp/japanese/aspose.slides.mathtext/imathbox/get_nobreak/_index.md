---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "改行なし。このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。true の場合、ボックス内で改行は発生しません。これは、1 つ以上の二項演算子からなる演算子エミュレータにとって重要になる場合があります。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。既定値: true"
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() メソッド

改行なし。このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。true の場合、ボックス内で改行は発生しません。これは、1 つ以上の二項演算子からなる演算子エミュレータにとって重要になる場合があります。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。既定値: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## 備考

例:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 参考

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)