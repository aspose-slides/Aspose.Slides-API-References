---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，以确定 PDF 文档中图像的分辨率。
type: docs
weight: 365
url: /zh/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) 方法

设置一个值，以确定 PDF 文档中图像的分辨率。

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## 备注

属性会影响文件大小、导出时间和图像质量。

默认值为 **96**。

此参数的效果取决于少数因素。算法尝试根据属性值、源图像大小和图像帧大小获得最佳输出图像尺寸。使用相似的属性值可能会得到相同的结果。建议使用 16 或 32 的步长以获得明显的效果。

写入 **float**。

## 另见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)