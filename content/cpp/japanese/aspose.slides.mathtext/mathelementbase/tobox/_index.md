---
title: ToBox()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素を、方程式やその他の数式テキストの構成要素をグループ化するために使用される非表示のボックス（論理的なグルーピング）に配置します。箱で囲まれたオブジェクトは、（例として）配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、内部で改行が許可されないようにグループ化されたりします。
type: docs
weight: 261
url: /ja/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() メソッド


この要素を、方程式やその他の数式テキストの構成要素をグループ化するために使用される、非表示の箱（論理的なグルーピング）に配置します。箱で囲まれたオブジェクトは、（例として）配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、改行を許可しないようにグループ化されたりできます。

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### 戻り値

この要素が内部に配置された論理ボックス
## 備考



例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBox](../../imathbox/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)