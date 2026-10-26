---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーションされたテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの期間のパーセンテージを指定します。負の値は秒単位の遅延を指定します。float を取得します。
type: docs
weight: 300
url: /ja/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() メソッド


アニメーションされたテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの期間のパーセンテージを指定します。負の値は秒単位の遅延を指定します。**float** を取得します。

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## 備考


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 参照

* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)