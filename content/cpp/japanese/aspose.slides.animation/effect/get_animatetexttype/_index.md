---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアニメーションテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて一度にアニメーション化できます。AnimateTextType を参照してください。
type: docs
weight: 274
url: /ja/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() メソッド

エフェクトのアニメーションテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて一度にアニメーション化できます。参照 [AnimateTextType](../../animatetexttype/)。

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
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

* Enum [AnimateTextType](../../animatetexttype/)
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)