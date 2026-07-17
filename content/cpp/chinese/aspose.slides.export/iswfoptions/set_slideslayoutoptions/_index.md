---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 参考
description: 在导出演示文稿时设置幻灯片在页面上的放置模式 ISlidesLayoutOptions。此属性不支持分配类型为 Aspose.Slides.Export.HandoutLayoutingOptions 的对象
type: docs
weight: 404
url: /zh/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 方法

设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。此属性不支持分配类型为 **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** 的对象

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## 备注

示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 类 [ISwfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)