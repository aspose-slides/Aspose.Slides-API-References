---
title: set_JpegQuality()
second_title: Aspose.Slides C++ API 参考
description: 设置一个值，用于确定 PDF 文档中 JPEG 图像的质量。写入 uint8_t。
type: docs
weight: 196
url: /zh/aspose.slides.export/ipdfoptions/set_jpegquality/
---
## IPdfOptions::set_JpegQuality(uint8_t) 方法


设置一个值，用于确定 PDF 文档中 JPEG 图像的质量。写入 **uint8_t**。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_JpegQuality(uint8_t value)=0
```

## 备注


仅在文档包含 JPEG 图像时才生效。

在以 PDF 格式保存时使用此属性获取或设置文档内图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。
## 另请参见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)