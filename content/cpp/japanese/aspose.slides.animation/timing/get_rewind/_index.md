---
title: get_Rewind()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、エフェクトの再生が完了したときに巻き戻すかどうかを指定します。読み取り bool.
type: docs
weight: 235
url: /ja/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() メソッド

この属性は、エフェクトの再生が完了したときに巻き戻すかどうかを指定します。読み取り **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

## 関連項目

* クラス [Timing](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)