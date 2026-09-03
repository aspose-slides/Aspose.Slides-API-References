---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
返回段落的圖像。

### 返回
包含已渲染段落的圖像，若無法在其父集合中找到段落、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則返回 **None**。

```python
def get_image(self):
    ...
```

## get_image {#float-float}
返回具有指定縮放比例的段落圖像。

### 返回
包含已渲染段落的圖像，若無法在其父集合中找到段落、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則返回 **None**。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 套用於段落圖像的水平縮放係數。 |
| scale_y | **float** | 套用於段落圖像的垂直縮放係數。 |

### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IParagraph`](/slides/python-net/zh-hant/aspose.slides/iparagraph)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)