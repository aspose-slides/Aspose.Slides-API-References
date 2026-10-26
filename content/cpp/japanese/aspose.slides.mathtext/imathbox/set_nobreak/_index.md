---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "改行なし。 このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。 true の場合、ボックス内で改行は発生しません。 これは、複数の二項演算子からなるオペレータ エミュレータにとって重要になる場合があります。 この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。 デフォルト: true"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) メソッド

改行なし。 このプロパティはオブジェクトボックスの「unbreakable」プロパティを指定します。 true の場合、ボックス内部で改行は発生しません。 これは、複数の二項演算子からなるオペレータエミュレータにとって重要になる場合があります。 この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。 デフォルト: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 参照

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)