---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API 參考
description: 為效果定義後動畫類型。請閱讀 AfterAnimationType.
type: docs
weight: 222
url: /zh-hant/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() 方法


為效果定義後動畫類型。請閱讀 [AfterAnimationType](../../afteranimationtype/)。

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的後動畫更改為 "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 參見

* Enum [AfterAnimationType](../../afteranimationtype/)
* 類別 [IEffect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)