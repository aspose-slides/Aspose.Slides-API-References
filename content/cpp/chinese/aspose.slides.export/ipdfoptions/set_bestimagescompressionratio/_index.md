---
title: set_BestImagesCompressionRatio()
second_title: Aspose.Slides for C++ API 参考
description: 指示是否应自动为每个图像选择最有效的压缩（而不是默认压缩）。如果设置为 bool.true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而导致生成的 PDF 文档体积更小。
type: docs
weight: 40
url: /zh/aspose.slides.export/ipdfoptions/set_bestimagescompressionratio/
---
## IPdfOptions::set_BestImagesCompressionRatio(bool) 方法

指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 **bool**.true，则在演示文稿中的每个图像都会选择最合适的压缩算法，从而导致生成的 PDF 文档体积更小。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_BestImagesCompressionRatio(bool value)=0
```

## 备注

最佳图像压缩比的选择计算量大且会占用额外的 RAM，且此选项默认是 **bool**.false。

默认是 **bool**.false。 
## 另见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)