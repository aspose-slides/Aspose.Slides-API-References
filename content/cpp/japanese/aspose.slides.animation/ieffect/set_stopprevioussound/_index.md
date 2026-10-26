---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。bool を記述します。
type: docs
weight: 209
url: /ja/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) メソッド


この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。**bool** を記述します。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 2枚目のスライドの最初のエフェクトを取得します。
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 2番目のエフェクトの Enhancements/Sound を "Stop Previous Sound" に変更します。
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 参照

* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)