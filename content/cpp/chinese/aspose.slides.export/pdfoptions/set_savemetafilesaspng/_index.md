---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides C++ API 参考
description: True 表示将演示文稿中使用的所有元文件转换为 PNG 图像。写入 bool.
type: docs
weight: 339
url: /zh/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) 方法


True 表示将演示文稿中使用的所有元文件转换为 PNG 图像。写入 **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## 备注


默认是 **true**。Pdf 文档可以包含矢量图形和栅格图像。如果 SaveMetafilesAsPng 设置为 true，则源 Metafile 图像会转换为 Png 格式并以栅格图像保存到 Pdf 中。如果 SaveMetafilesAsPng 设置为 false，则源 Metafile 会转换为 Pdf 矢量图形。每种方法各有优缺点。例如，如果 Metafile 被转换为 PNG，则在后续文档缩放时可能会出现一定的质量损失。如果 Metafile 被转换为 Pdf 矢量图形，则可能会出现 Pdf 查看工具的性能问题。 
## 参见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)