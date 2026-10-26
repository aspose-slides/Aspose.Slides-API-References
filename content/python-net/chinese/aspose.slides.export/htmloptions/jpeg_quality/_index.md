---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality 属性
返回或设置一个决定 PDF 文档中 JPEG 图像质量的值。
            读/写 **int**.


### 备注

仅当文档包含 JPEG 图像时才有效。


在以 PDF 格式保存时，使用此属性获取或设置文档中图像的质量。
            该值范围为 0 到 100，其中 0 表示质量最差但压缩最大，100 表示质量最佳但压缩最小。


默认值为 **95** 。

### 定义:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### 另请参见
* 类 [`HtmlOptions`](/slides/python-net/zh/aspose.slides.export/htmloptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)