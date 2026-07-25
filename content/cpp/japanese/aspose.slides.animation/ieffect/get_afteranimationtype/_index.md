---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのアフターアニメーションタイプを定義します。AfterAnimationType を参照してください。
type: docs
weight: 222
url: /ja/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() メソッド


エフェクトのアフターアニメーションタイプを定義します。[AfterAnimationType](../../afteranimationtype/) を参照してください。

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトのアフターアニメーションを「次のマウスクリックで非表示」に変更します。
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 参照

* 列挙型 [AfterAnimationType](../../afteranimationtype/)
* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)