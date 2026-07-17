---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 参考
description: True 表示将演示文稿中使用的所有 metafile 转换为 PNG 图像。读取 bool.
type: docs
weight: 287
url: /zh/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() 方法

True 表示将演示文稿中使用的所有 metafiles 转换为 PNG 图像。读取 **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## 备注

默认值为 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果将 SaveMetafilesAsPng 设置为 true，则将源 Metafile 图像转换为 Png 格式并保存为 Pdf 的光栅图像。如果将 SaveMetafilesAsPng 设置为 false，则将源 Metafile 转换为 Pdf 矢量图形。每种方法都有其优缺点。例如，如果 Metafile 被转换为 PNG，则在后续文档缩放时可能会出现一定的质量损失。如果 Metafile 被转换为 Pdf 矢量图形，则可能会在 Pdf 查看工具中出现性能问题。

## 另见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)