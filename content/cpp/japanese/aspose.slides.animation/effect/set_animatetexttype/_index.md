---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアニメーションテキストタイプを定義します。シェイプテキストは文字単位、単語単位、または一括でアニメーション化できます。AnimateTextType を書きます。
type: docs
weight: 287
url: /ja/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) メソッド

エフェクトのアニメーションテキストタイプを定義します。シェイプテキストは文字単位、単語単位、または一括でアニメーション化できます。[AnimateTextType](../../animatetexttype/)を書きます。

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 参照

* 列挙型 [AnimateTextType](../../animatetexttype/)
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)