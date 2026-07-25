---
title: get_AfterAnimationColor()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアフターアニメーションカラーを定義します。IColorFormat を参照してください。
type: docs
weight: 248
url: /ja/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() メソッド


エフェクトのアフターアニメーションカラーを定義します。参照 [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトのアフターアニメーションタイプを "Color" に変更します。
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// エフェクトのアフターアニメーションカラーを設定します。
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IColorFormat](../../../aspose.slides/icolorformat/)
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)