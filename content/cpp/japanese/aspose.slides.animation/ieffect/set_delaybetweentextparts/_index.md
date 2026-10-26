---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーションテキストパート（単語または文字）間の遅延を定義します。正の値はエフェクト期間の割合を指定します。負の値は遅延を秒単位で指定します。float で記述します。
type: docs
weight: 313
url: /ja/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) メソッド

アニメーションテキストパート（単語または文字）間の遅延を定義します。正の値はエフェクト期間の割合を指定します。負の値は遅延を秒で指定します。**float** で記述します。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
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