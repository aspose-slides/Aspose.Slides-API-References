---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image(self) {#}
返回段落的圖像。

### Returns

包含已渲染段落的圖像，若段落在其父集合中找不到、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則返回 **None**



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
返回具有指定縮放比例的段落圖像。

### Returns

包含已渲染段落的圖像，若段落在其父集合中找不到、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則返回 **None**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 套用於段落圖像的水平縮放因子。 |
| scale_y | **float** | 套用於段落圖像的垂直縮放因子。 |



### See Also
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`Paragraph`](/slides/python-net/zh-hant/aspose.slides/paragraph)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)