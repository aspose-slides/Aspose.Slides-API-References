---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个用于确定 PDF 文档中图像分辨率的值。
type: docs
weight: 313
url: /zh/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() method

返回一个用于确定 PDF 文档中图像分辨率的值。

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## 备注

属性会影响文件大小、导出时间和图像质量。

默认值为 **96**。

此参数的影响取决于少数因素。算法尝试根据属性值、源图像大小和图像框大小获得最佳输出图像尺寸。使用相似的属性值可能会得到相同的结果。建议使用 16 或 32 的步长以获得明显的效果。

读取 **float**。 
## 另请参见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)