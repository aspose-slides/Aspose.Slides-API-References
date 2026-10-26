---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。bool を読み取ります。
type: docs
weight: 196
url: /ja/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() メソッド


この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。**bool** を読み取ります。

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 2番目のスライドの最初のエフェクトを取得
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 2番目のエフェクトの Enhancements/Sound を「Stop Previous Sound」に変更する
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 参照

* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)