---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API 參考
description: 為效果定義動畫文字類型。形狀文字可以按字母、按單詞或一次性全部動畫化。請閱讀 AnimateTextType。
type: docs
weight: 274
url: /zh-hant/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() 方法

為效果定義動畫文字類型。形狀文字可以按字母、按單詞或一次性全部動畫化。請參閱 [AnimateTextType](../../animatetexttype/)。

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另見

* Enum [AnimateTextType](../../animatetexttype/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)