---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 参考
description: 设置在导出演示文稿时幻灯片在页面上的放置模式 ISlidesLayoutOptions。
type: docs
weight: 170
url: /zh/aspose.slides.export/itiffoptions/set_slideslayoutoptions/
---
## ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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