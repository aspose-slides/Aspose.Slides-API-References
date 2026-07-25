---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: 基本的なプレースホルダー シェイプを返します（現在のシェイプが継承されているレイアウトおよび/またはマスタースライドからのシェイプ）。
type: docs
weight: 638
url: /ja/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() メソッド

基本的なプレースホルダー シェイプを返します（現在のシェイプが継承されているレイアウトおよび/またはマスタースライドからのシェイプ）。

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## 備考

現在のシェイプが継承されていない場合、null が返されます。

```cpp
// プレースホルダー シェイプのすべての (マスター/レイアウト/スライド) アニメーション効果を取得します
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)