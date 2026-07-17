---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 参考
description: 在导出演示文稿时设置幻灯片在页面上的放置模式 ISlidesLayoutOptions.
type: docs
weight: 14
url: /zh/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 方法

设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 类 [HtmlOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)