---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーション化されたテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの継続時間のパーセンテージを指定します。負の値は秒単位の遅延を指定します。float を読み取ります。
type: docs
weight: 300
url: /ja/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() メソッド

アニメーション化されたテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの継続時間のパーセンテージを指定します。負の値は秒単位の遅延を指定します。**float** を読み取ります。

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)