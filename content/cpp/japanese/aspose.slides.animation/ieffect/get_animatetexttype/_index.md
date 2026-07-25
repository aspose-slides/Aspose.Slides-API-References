---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアニメーションテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて一度にアニメーション化できます。AnimateTextType を参照してください。
type: docs
weight: 274
url: /ja/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() メソッド


エフェクトのアニメーションテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて一度にアニメーション化できます。[AnimateTextType](../../animatetexttype/) を参照してください。

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトのアニメーションテキストタイプを "By letter" に変更します
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 参照

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)