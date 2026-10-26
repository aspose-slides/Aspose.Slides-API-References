---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ APIリファレンス
description: この属性は、エフェクトがスライドの最後まで繰り返されるかどうかを指定します。bool を読み取ります。
type: docs
weight: 131
url: /ja/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() メソッド

この属性は、エフェクトがスライドの最後まで繰り返されるかどうかを指定します。**bool** を読み取ります。

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## 備考

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 参照

* クラス [Timing](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)