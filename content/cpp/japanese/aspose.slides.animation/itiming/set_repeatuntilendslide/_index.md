---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、エフェクトがスライドの最後まで繰り返すかどうかを指定します。bool を記述します。
type: docs
weight: 144
url: /ja/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) method


この属性は、エフェクトがスライドの最後まで繰り返すかどうかを指定します。**bool** を記述します。

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 最初のスライドのエフェクトシーケンスを取得します
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// メインシーケンスの最初のエフェクトを取得します。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// エフェクトの Timing/Repeat を "Until End of Slide" に変更します
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 関連項目

* クラス [ITiming](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)