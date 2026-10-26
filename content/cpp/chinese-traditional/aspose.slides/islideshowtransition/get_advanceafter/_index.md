---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定簡報在一定時間後是否會移動到下一張投影片。讀取 bool.
type: docs
weight: 105
url: /zh-hant/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() 方法

此屬性指定簡報在一定時間後是否會移動到下一張投影片。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 取得第一張投影片的過渡效果
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 檢查 Advance Slide After 旗標是否已勾選
if (slideTransition->get_AdvanceAfter())
{
    // 取得 Advance Slide After 時間值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 參見

* Class [ISlideShowTransition](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)