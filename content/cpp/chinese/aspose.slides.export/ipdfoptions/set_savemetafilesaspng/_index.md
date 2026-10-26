---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 参考
description: True 表示将演示文稿中使用的所有元文件转换为 PNG 图像。写入 bool.
type: docs
weight: 300
url: /zh/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) 方法

True 表示将演示文稿中使用的所有元文件转换为 PNG 图像。写入 **bool**。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## 备注

默认是 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 设置为 true，则源 Metafile 图像将转换为 Png 格式并作为光栅图像保存到 Pdf 中。如果 SaveMetafilesAsPng 设置为 false，则源 Metafile 将转换为 Pdf 矢量图形。每种方法都有优势和劣势。例如，如果 Metafile 被转换为 PNG，则在结果文档缩放时可能会出现一定的质量损失。如果 Metafile 被转换为 Pdf 矢量图形，则可能会出现 Pdf 查看工具的性能问题。

## 另请参见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)