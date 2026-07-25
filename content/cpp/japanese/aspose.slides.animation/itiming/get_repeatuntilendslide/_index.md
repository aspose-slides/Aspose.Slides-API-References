---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ APIリファレンス
description: この属性は、エフェクトがスライドの最後まで繰り返されるかどうかを指定します。読み取り bool。
type: docs
weight: 131
url: /ja/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() メソッド

この属性は、エフェクトがスライドの最後まで繰り返されるかどうかを指定します。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
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

* クラス [ITiming](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)