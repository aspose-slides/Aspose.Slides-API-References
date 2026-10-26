---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、または一度にすべてアニメーション化できます。AnimateTextType を記述します。
type: docs
weight: 287
url: /ja/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) メソッド


エフェクトのアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、または一度にすべてアニメーション化できます。[AnimateTextType](../../animatetexttype/)を書き込みます。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトのアニメートテキストタイプを "By letter" に変更します。
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 参照

* 列挙体 [AnimateTextType](../../animatetexttype/)
* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)