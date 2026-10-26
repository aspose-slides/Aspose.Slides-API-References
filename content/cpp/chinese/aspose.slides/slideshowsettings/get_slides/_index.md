---
title: get_Slides()
second_title: Aspose.Slides C++ API 参考
description: 幻灯片范围
type: docs
weight: 118
url: /zh/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const 方法


[Slides](../../) 范围

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [SlidesRange](../../slidesrange/)
* 类 [SlideShowSettings](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)