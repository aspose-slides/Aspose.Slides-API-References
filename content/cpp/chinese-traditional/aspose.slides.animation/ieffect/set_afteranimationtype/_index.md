---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API 參考
description: 為效果定義後動畫類型。寫入 AfterAnimationType.
type: docs
weight: 235
url: /zh-hant/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) 方法

為效果定義後動畫類型。寫入 [AfterAnimationType](../../afteranimationtype/)。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 獲取第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的「後動畫」更改為「在下一次滑鼠點擊時隱藏」。
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 另請參閱

* 列舉 [AfterAnimationType](../../afteranimationtype/)
* 類別 [IEffect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)