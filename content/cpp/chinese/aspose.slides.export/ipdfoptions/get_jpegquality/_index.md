---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个值，用于确定 PDF 文档中 JPEG 图像的质量。读取 uint8_t.
type: docs
weight: 183
url: /zh/aspose.slides.export/ipdfoptions/get_jpegquality/
---
## IPdfOptions::get_JpegQuality() 方法

返回一个值，用于确定 PDF 文档中 JPEG 图像的质量。读取 **uint8_t**。

```cpp
virtual uint8_t Aspose::Slides::Export::IPdfOptions::get_JpegQuality()=0
```

## 备注

仅在文档包含 JPEG 图像时才有效。

使用此属性在将文档保存为 PDF 格式时获取或设置文档中图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩最大，100 表示质量最佳但压缩最小。

默认值为 **100**。

## 另请参见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)