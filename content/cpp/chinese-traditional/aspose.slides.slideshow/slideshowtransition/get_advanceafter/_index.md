---
title: get_AdvanceAfter()
second_title: Aspose.Slides C++ API 參考
description: 此屬性指定投影片在特定時間後是否會移動至下一張投影片。讀取 bool.
type: docs
weight: 105
url: /zh-hant/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() 方法


此屬性指定投影片在特定時間後是否會自動切換至下一張投影片。讀取 **bool**。

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 取得第一個投影片轉場
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 檢查是否勾選了 Advance Slide After 標誌
if (slideTransition->get_AdvanceAfter())
{
    // 取得 Advance Slide After 時間值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 參見

* 類別 [SlideShowTransition](../)
* 命名空間 [Aspose::Slides::SlideShow](../../)
* 函式庫 [Aspose.Slides](../../../)