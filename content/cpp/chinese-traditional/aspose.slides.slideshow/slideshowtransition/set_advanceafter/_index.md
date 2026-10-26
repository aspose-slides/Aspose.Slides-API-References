---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性指定投影片放映在特定時間後是否會移至下一張投影片。寫入 bool.
type: docs
weight: 118
url: /zh-hant/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) 方法

此屬性指定投影片放映在特定時間後是否會移至下一張投影片。寫入 **bool**。

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 取得第一張投影片過渡
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 檢查 Advance Slide After 旗標是否已勾選
if (slideTransition->get_AdvanceAfter())
{
    // 取得 Advance Slide After 時間值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 另見

* 類別 [SlideShowTransition](../)
* 命名空間 [Aspose::Slides::SlideShow](../../)
* 程式庫 [Aspose.Slides](../../../)