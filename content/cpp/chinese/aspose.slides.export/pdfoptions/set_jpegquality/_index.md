---
title: set_JpegQuality()
second_title: Aspose.Slides C++ API 参考
description: 设置一个值，用于确定 PDF 文档内 JPEG 图像的质量。写入 uint8_t。
type: docs
weight: 235
url: /zh/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) 方法

设置一个值，用于确定 PDF 文档内 JPEG 图像的质量。写入 **uint8_t**。

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## 备注

仅当文档包含 JPEG 图像时才有效。

使用此属性在以 PDF 格式保存文档时获取或设置文档内图像的质量。该值可以在 0 到 100 之间变化，其中 0 表示质量最差但压缩最大，100 表示质量最佳但压缩最小。

默认值为 **100**。

## 另请参见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)