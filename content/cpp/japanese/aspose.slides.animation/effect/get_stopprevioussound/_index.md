---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ APIリファレンス
description: この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り bool。
type: docs
weight: 196
url: /ja/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() メソッド


この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 2番目のスライドの最初のエフェクトを取得します。
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 2番目のエフェクトの拡張機能/サウンドを "Stop Previous Sound" に変更します。
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 参照

* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)