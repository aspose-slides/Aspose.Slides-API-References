---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API 參考
description: 定義效果的後置動畫類型。請閱讀 AfterAnimationType.
type: docs
weight: 222
url: /zh-hant/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() 方法


定義效果的後置動畫類型。請閱讀 [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的後置動畫改為 "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 另見

* 列舉 [AfterAnimationType](../../afteranimationtype/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)