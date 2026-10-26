---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个决定 PDF 文档内部图像分辨率的值。
type: docs
weight: 352
url: /zh/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() 方法


返回一个确定 PDF 文档内部图像分辨率的值。

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## 备注


属性影响文件大小、导出时间和图像质量。

默认值为 **96**。

此参数的效果取决于少数因素。算法尝试根据属性值、源图像大小和图像框大小获得最佳输出图像尺寸。使用类似的属性值可能得到相同的结果。建议使用 16 或 32 的步长以获得明显效果。

读取 **float**。 

## 另见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)