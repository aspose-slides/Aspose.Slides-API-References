---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 参考
description: 获取在导出演示文稿时幻灯片在页面上放置的模式 ISlidesLayoutOptions.
type: docs
weight: 157
url: /zh/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() 方法


获取在导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
```

## 备注


示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 类 [ITiffOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)