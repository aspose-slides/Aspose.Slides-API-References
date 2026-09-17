---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality 属性
返回或设置一个值，以确定 PDF 文档中 JPEG 图像的质量。
            读/写 **int**.


### 备注

仅在文档包含 JPEG 图像时才有效。


使用此属性在保存为 PDF 格式时获取或设置文档中图像的质量。
            该值可以在 0 到 100 之间变化，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。


默认值为 **100** .

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
* 类 [`IPdfOptions`](/slides/python-net/zh/aspose.slides.export/ipdfoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)