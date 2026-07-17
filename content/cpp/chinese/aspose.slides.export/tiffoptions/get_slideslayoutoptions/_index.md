---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 参考
description: 获取在导出演示文稿时幻灯片在页面上的放置模式 ISlidesLayoutOptions。
type: docs
weight: 170
url: /zh/aspose.slides.export/tiffoptions/get_slideslayoutoptions/
---
## TiffOptions::get_SlidesLayoutOptions() 方法

获取在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::TiffOptions::get_SlidesLayoutOptions() override
```

## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 类 [TiffOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)