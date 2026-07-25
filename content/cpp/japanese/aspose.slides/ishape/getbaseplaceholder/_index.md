---
title: GetBasePlaceholder()
second_title: Aspose.Slides の C++ API リファレンス
description: 基本的なプレースホルダーシェイプを返します（レイアウトやマスタースライドから取得され、現在のシェイプが継承しているシェイプ）。
type: docs
weight: 573
url: /ja/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() メソッド

基本的なプレースホルダーシェイプを返します（レイアウトおよび/またはマスタースライドから取得され、現在のシェイプが継承しているシェイプ）。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## 備考

現在のシェイプが継承されていない場合、null が返されます。

```cpp
// プレースホルダーシェイプの (マスター/レイアウト/スライド) のすべてのアニメーション効果を取得する
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
* クラス [IShape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)