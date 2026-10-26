---
title: get_Handout()
second_title: Aspose.Slides for C++ API 参考
description: 指定在页面 HandoutType 上将放置多少张幻灯片以及它们的顺序。
type: docs
weight: 1
url: /zh/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const 方法

指定在页面 [HandoutType](../../handouttype/) 上将放置多少张幻灯片以及它们的顺序。

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## 备注

默认值为 **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 另请参见

* 枚举 [HandoutType](../../handouttype/)
* 类 [HandoutLayoutingOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)