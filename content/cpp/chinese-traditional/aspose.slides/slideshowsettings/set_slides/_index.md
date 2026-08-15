---
title: set_Slides()
second_title: Aspose.Slides for C++ API 參考文件
description: 投影片範圍
type: docs
weight: 131
url: /zh-hant/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) 方法

[Slides](../../) 範圍

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [SlidesRange](../../slidesrange/)
* 類別 [SlideShowSettings](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)