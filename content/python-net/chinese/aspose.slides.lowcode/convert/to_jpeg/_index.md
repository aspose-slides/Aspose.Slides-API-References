---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
转换输入的演示文稿为一组 JPEG 格式的图像。  
            如果输出文件名写为 "myPath/myFilename.jpeg"，  
            结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入演示文稿。 |
| output_file_name | **str** | 输出文件名。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
转换输入的演示文稿为一组 JPEG 格式的图像。  
            如果输出文件名写为 "myPath/myFilename.jpeg"，  
            结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入演示文稿 |
| output_file_name | **str** | 输出文件名。 |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 每个生成图像的大小。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
转换输入的演示文稿为一组 JPEG 格式的图像。  
            如果输出文件名写为 "myPath/myFilename.jpeg"，  
            结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入演示文稿。 |
| output_file_name | **str** | 输出文件名。 |
| scale | **float** | 相对于原始幻灯片大小的输出图像的缩放因子。 |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### 参见
* 类 [`Convert`](/slides/python-net/zh/aspose.slides.lowcode/convert)
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 类 [`Size`](/slides/python-net/zh/aspose.slides/size)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)