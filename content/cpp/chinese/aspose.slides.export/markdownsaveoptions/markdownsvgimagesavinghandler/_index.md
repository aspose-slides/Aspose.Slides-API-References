---
title: MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for C++ API 参考文档
description: 在 Markdown 导出期间，对每个 SVG 图像调用此处理程序。返回 true 以使用指定的链接，或返回 false 以应用默认的保存逻辑。
type: docs
weight: 313
url: /zh/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef

在 Markdown 导出期间，对每个 SVG 图像调用此处理程序。 
返回 **true** 以使用指定的 *link* ， 
或返回 **false** 以应用默认的保存逻辑。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```

## 另请参见

* 类 [MarkdownSaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)