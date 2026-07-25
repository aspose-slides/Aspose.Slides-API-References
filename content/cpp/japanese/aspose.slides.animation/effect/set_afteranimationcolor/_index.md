---
title: set_AfterAnimationColor()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアフターアニメーションカラーを定義します。IColorFormatを書き込みます。
type: docs
weight: 261
url: /ja/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) メソッド

エフェクトのアフターアニメーションカラーを定義します。[IColorFormat](../../../aspose.slides/icolorformat/)を書き込みます。

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## 備考

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IColorFormat](../../../aspose.slides/icolorformat/)
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)