---
title: set_Rewind()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、エフェクトの再生が完了したときに巻き戻すかどうかを指定します。書き込む型は bool です。
type: docs
weight: 248
url: /ja/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) メソッド

この属性は、エフェクトの再生が完了したときに巻き戻すかどうかを指定します。書き込む型は **bool** です。

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## 参照

* クラス [Timing](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)