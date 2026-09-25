---
title: to_png method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
将输入的演示文稿转换为一组 PNG 格式的图像。  
如果将输出文件名指定为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入的演示文稿。 |
| output_file_name | **str** | 输出文件名。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
将输入的演示文稿转换为一组 PNG 格式的图像。  
如果将输出文件名指定为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入的演示文稿 |
| output_file_name | **str** | 输出文件名。 |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 每个生成图像的大小。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
将输入的演示文稿转换为一组 PNG 格式的图像。  
如果将输出文件名指定为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入的演示文稿。 |
| output_file_name | **str** | 输出文件名。 |
| scale | **float** | 相对于原始幻灯片大小的输出图像缩放因子。 |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### 另见
* 类 [`Convert`](/slides/python-net/zh/aspose.slides.lowcode/convert)
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 类 [`Size`](/slides/python-net/zh/aspose.slides/size)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)