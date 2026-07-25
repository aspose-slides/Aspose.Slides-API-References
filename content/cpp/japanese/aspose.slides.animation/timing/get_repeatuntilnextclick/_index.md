---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides 用 C++ API リファレンス
description: この属性は、エフェクトが次のクリックまで繰り返されるかどうかを指定します。読み取り bool.
type: docs
weight: 157
url: /ja/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() method


この属性は、エフェクトが次のクリックまで繰り返されるかどうかを指定します。読み取り **bool**。

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
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

## 関連項目

* クラス [Timing](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)