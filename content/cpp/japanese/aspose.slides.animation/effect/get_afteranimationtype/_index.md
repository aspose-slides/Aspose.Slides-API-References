---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトの後続アニメーション タイプを定義します。AfterAnimationType を参照してください。
type: docs
weight: 222
url: /ja/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() メソッド


エフェクトの後続アニメーション タイプを定義します。[AfterAnimationType](../../afteranimationtype/) を参照してください。

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
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
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)