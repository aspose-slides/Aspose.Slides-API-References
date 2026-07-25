---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトの後アニメーションタイプを定義します。AfterAnimationTypeを書き込みます。
type: docs
weight: 235
url: /ja/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) メソッド

エフェクトの後アニメーションタイプを定義します。[AfterAnimationType](../../afteranimationtype/)を書き込みます。

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## 備考

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトの After animation を "Hide on Next Mouse Click" に変更します。
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 参照

* Enum [AfterAnimationType](../../afteranimationtype/)
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)