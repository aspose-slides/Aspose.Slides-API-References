---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API 參考
description: 定義動畫文字部件（單字或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。讀取 float.
type: docs
weight: 300
url: /zh-hant/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() 方法


定義動畫文字部件（單字或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。讀取 **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 另見

* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)