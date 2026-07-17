---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API 参考
description: 设置用于确定 PDF 文档中图像分辨率的值。
type: docs
weight: 326
url: /zh/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) 方法


设置用于确定 PDF 文档中图像分辨率的值。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## 备注


该属性会影响文件大小、导出时间和图像质量。

默认值为 **96**。

此参数的效果取决于几个因素。算法会根据属性值、源图像大小和图像框大小尝试获取最佳输出图像尺寸。使用相似的属性值可能会得到相同的结果。建议使用 16 或 32 的步长以获得明显的效果。

写入 **float**。 
## 另请参见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)