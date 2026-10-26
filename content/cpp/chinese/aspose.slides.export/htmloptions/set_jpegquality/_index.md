---
title: set_JpegQuality()
second_title: Aspose.Slides C++ API 参考
description: 设置一个值，用于确定 PDF 文档中 JPEG 图像的质量。写入 uint8_t.
type: docs
weight: 157
url: /zh/aspose.slides.export/htmloptions/set_jpegquality/
---
## HtmlOptions::set_JpegQuality(uint8_t) 方法

设置一个值，用于确定 PDF 文档中 JPEG 图像的质量。写入 **uint8_t**。

```cpp
void Aspose::Slides::Export::HtmlOptions::set_JpegQuality(uint8_t value) override
```

## 备注

仅在文档包含 JPEG 图像时才生效。

在保存为 PDF 格式时，使用此属性获取或设置文档中图像的质量。该值可以在 0 到 100 之间变化，其中 0 表示最差质量但最大压缩，100 表示最佳质量但最小压缩。

默认值为 **95**。

## 另请参阅

* 类 [HtmlOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)