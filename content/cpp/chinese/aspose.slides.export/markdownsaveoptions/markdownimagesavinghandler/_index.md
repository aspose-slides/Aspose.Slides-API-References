---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides C++ API 参考
description: 在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）调用。返回 true 以使用指定的链接，或 false 以应用默认的保存逻辑。
type: docs
weight: 300
url: /zh/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）调用。

返回 **true** 以使用指定的 *链接*，

或 **false** 以应用默认的保存逻辑。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## 另请参见

* 类 [MarkdownSaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)