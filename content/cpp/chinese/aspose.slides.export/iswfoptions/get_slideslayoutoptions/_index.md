---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API 参考
description: 获取在导出演示文稿时，幻灯片在页面上放置的模式 ISlidesLayoutOptions。此属性不支持分配类型为 Aspose.Slides.Export.HandoutLayoutingOptions 的对象。
type: docs
weight: 391
url: /zh/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() 方法


获取在导出演示文稿 [ISlidesLayoutOptions](../../islideslayoutoptions/) 时，幻灯片在页面上放置的模式。此属性不支持分配类型为 **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** 的对象

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
```

## 备注


示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 类 [ISwfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)