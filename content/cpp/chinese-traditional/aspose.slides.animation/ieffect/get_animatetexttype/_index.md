---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API 參考
description: 定義效果的動畫文字類型。形狀文字可以逐字母、逐單詞或一次性全部動畫化。請閱讀 AnimateTextType.
type: docs
weight: 274
url: /zh-hant/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() 方法

定義效果的動畫文字類型。形狀文字可以逐字母、逐單詞或一次性全部動畫化。請閱讀 [AnimateTextType](../../animatetexttype/)。

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的動畫文字類型變更為「逐字母」
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另請參閱

* 列舉 [AnimateTextType](../../animatetexttype/)
* 類別 [IEffect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)