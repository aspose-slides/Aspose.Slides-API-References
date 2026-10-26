---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性指定投影片是否會在特定時間後移動到下一張投影片。寫入 bool.
type: docs
weight: 118
url: /zh-hant/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) 方法


此屬性指定投影片是否會在特定時間後移動到下一張投影片。寫入 **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 取得第一張投影片過場
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 檢查 Advance Slide After 旗標是否已設定
if (slideTransition->get_AdvanceAfter())
{
    // 取得 Advance Slide After 時間值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 另請參閱

* 類別 [ISlideShowTransition](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)