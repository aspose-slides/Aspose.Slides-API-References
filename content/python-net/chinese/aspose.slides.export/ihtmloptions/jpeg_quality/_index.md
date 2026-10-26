---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality 属性
返回或设置一个值，以确定 PDF 文档中 JPEG 图像的质量。
            读/写 **int**.


### 备注

仅当文档包含 JPEG 图像时才有效。


在以 PDF 格式保存时，可使用此属性获取或设置文档中图像的质量。
            该值范围为 0 到 100，其中 0 表示最差质量但最大压缩，100 表示最佳质量但最小压缩。


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


### 另见
* 类 [`IHtmlOptions`](/slides/python-net/zh/aspose.slides.export/ihtmloptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)