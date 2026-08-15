---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API 參考
description: 定義效果的動畫文字類型。形狀文字可以以字母、單詞或一次性全部進行動畫。寫入 AnimateTextType。
type: docs
weight: 287
url: /zh-hant/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) method

定義效果的動畫文字類型。形狀文字可以逐字母、逐單詞或一次性全部動畫。寫入 [AnimateTextType](../../animatetexttype/)。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的動畫文字類型更改為「By letter」
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另見

* 列舉 [AnimateTextType](../../animatetexttype/)
* 類別 [IEffect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)