---
title: set_Slides()
second_title: Aspose.Slides for C++ API 参考
description: 幻灯片范围
type: docs
weight: 131
url: /zh/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) 方法


[Slides](../../) 范围

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [SlidesRange](../../slidesrange/)
* 类 [SlideShowSettings](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)