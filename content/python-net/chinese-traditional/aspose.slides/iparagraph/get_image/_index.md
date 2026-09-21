---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image(self) {#}
返回段落的圖像。

### 回傳值

包含已渲染段落的圖像，若找不到段落於其父集合、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則為 **None**



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
返回具有指定縮放比例的段落圖像。

### 回傳值

包含已渲染段落的圖像，若找不到段落於其父集合、沒有有效的渲染邊界，或在渲染圖像時發生錯誤，則為 **None**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 應用於段落圖像的水平縮放因子。 |
| scale_y | **float** | 應用於段落圖像的垂直縮放因子。 |



### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IParagraph`](/slides/python-net/zh-hant/aspose.slides/iparagraph)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)