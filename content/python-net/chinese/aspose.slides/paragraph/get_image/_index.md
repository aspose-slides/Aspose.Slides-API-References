---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
返回段落的图像。

### 返回

包含已渲染段落的图像，或 **None**  
如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时发生错误。

```python
def get_image(self):
    ...
```

## get_image {#float-float}
返回带有指定比例的段落图像。

### 返回

包含已渲染段落的图像，或 **None**  
如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时发生错误。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_x | **float** | 应用于段落图像的水平缩放因子。 |
| scale_y | **float** | 应用于段落图像的垂直缩放因子。 |

### 另请参见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`Paragraph`](/slides/python-net/zh/aspose.slides/paragraph)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)