---
title: set_AnimateTextType()
second_title: Aspose.Slides C++ API 參考
description: 定義效果的動畫文字類型。形狀文字可以逐字母、逐單詞或一次性全部動畫化。寫入 AnimateTextType。
type: docs
weight: 287
url: /zh-hant/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) 方法

定義效果的動畫文字類型。形狀文字可以逐字母、逐單詞或一次性全部動畫化。寫入 [AnimateTextType](../../animatetexttype/)。

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的動畫文字類型變更為 "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另請參閱

* 列舉 [AnimateTextType](../../animatetexttype/)
* 類 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)