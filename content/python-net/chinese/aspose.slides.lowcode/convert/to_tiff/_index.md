---
title: to_tiff method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
将输入的演示文稿转换为一组 TIFF 格式的图像。  
如果将输出文件名指定为 "myPath/myFilename.tiff"，则结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 为幻灯片编号。

```python
@staticmethod
def to_tiff(pres, output_file_name):
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

## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
使用自定义选项将输入的演示文稿转换为 TIFF 格式。  
如果将输出文件名指定为 "myPath/myFilename.tiff" 并且 `multipage` 为 `false`，则结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 为幻灯片编号。  
否则，如果 `multippage` 为 `true`，结果将是一个多页的 "myPath/myFilename.tiff" 文档。

```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 输入的演示文稿。 |
| output_file_name | **str** | 输出文件名。 |
| options | [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions) | TIFF 保存选项。 |
| multipage | **bool** | 指定生成的 TIFF 文档是否为多页。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### 另请参见
* 类 [`Convert`](/slides/python-net/zh/aspose.slides.lowcode/convert)
* 类 [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)