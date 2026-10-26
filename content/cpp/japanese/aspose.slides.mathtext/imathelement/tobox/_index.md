---
title: ToBox()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素を非表示のボックス（論理的なグルーピング）に配置します。このボックスは、数式やその他の数学テキストの構成要素をグループ化するために使用されます。たとえば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行点として機能したり、内部で改行が許可されないようにグループ化されたりします。
type: docs
weight: 274
url: /ja/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() メソッド

この要素を非表示のボックス（論理的なグルーピング）に配置します。このボックスは、数式やその他の数学テキストのインスタンスの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、たとえば整列点の有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、改行を許可しないようにグループ化されたりします。

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### 戻り値

この要素が内部に配置された論理ボックス

## 備考

例:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBox](../../imathbox/)
* クラス [IMathElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)