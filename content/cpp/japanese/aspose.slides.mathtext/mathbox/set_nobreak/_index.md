---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API リファレンス
description: "改行なし このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。true の場合、ボックス内で改行は発生しません。これは、複数の二項演算子で構成される演算子エミュレータにとって重要になることがあります。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。既定値: true"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) メソッド

No break このプロパティはオブジェクト ボックスの \"unbreakable\" プロパティを指定します。true の場合、ボックス内で改行は発生しません。これは、複数の二項演算子で構成される演算子エミュレータにとって重要になることがあります。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。既定値: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 関連項目

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)