---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、エフェクトが次のクリックまで繰り返されるかどうかを指定します。bool を記述します。
type: docs
weight: 170
url: /ja/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) メソッド

この属性は、エフェクトが次のクリックまで繰り返されるかどうかを指定します。**bool** を記述します。

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## 備考


```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## 参照

* クラス [ITiming](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)