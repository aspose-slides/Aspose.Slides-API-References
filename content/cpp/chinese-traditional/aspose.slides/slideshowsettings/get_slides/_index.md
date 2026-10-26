---
title: get_Slides()
second_title: Aspose.Slides for C++ API 參考
description: 投影片範圍
type: docs
weight: 118
url: /zh-hant/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const 方法


[Slides](../../) 範圍

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [SlidesRange](../../slidesrange/)
* 類別 [SlideShowSettings](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)