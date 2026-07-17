---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个确定 PDF 文档中 JPEG 图像质量的值。读取 uint8_t。
type: docs
weight: 222
url: /zh/aspose.slides.export/pdfoptions/get_jpegquality/
---
## PdfOptions::get_JpegQuality() 方法

返回一个确定 PDF 文档中 JPEG 图像质量的值。读取 **uint8_t**。

```cpp
uint8_t Aspose::Slides::Export::PdfOptions::get_JpegQuality() override
```

## 备注

仅当文档包含 JPEG 图像时才有效。

在保存为 PDF 格式时，使用此属性获取或设置文档中图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

## 另见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)