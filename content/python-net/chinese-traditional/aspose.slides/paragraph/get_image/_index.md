---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
傳回段落的影像。

### 返回
包含已渲染段落的影像，或 **None**
             若在其父集合中找不到段落、沒有有效的渲染範圍，或在渲染影像時發生錯誤。

```python
def get_image(self):
    ...
```

## get_image {#float-float}
傳回使用指定比例的段落影像。

### 返回
包含已渲染段落的影像，或 **None**
             若在其父集合中找不到段落、沒有有效的渲染範圍，或在渲染影像時發生錯誤。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 套用於段落影像的水平縮放因子。 |
| scale_y | **float** | 套用於段落影像的垂直縮放因子。 |

### 參見
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`Paragraph`](/slides/python-net/zh-hant/aspose.slides/paragraph)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)