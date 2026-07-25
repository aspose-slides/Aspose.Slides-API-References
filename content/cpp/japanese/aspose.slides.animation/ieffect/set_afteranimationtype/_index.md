---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトの後のアニメーション タイプを定義します。AfterAnimationType を記述します。
type: docs
weight: 235
url: /ja/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) メソッド


エフェクトの後のアニメーション タイプを定義します。[AfterAnimationType](../../afteranimationtype/)を書きます。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 参照

* 列挙型 [AfterAnimationType](../../afteranimationtype/)
* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)