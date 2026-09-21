---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
傳回形狀縮圖。
            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。

### 返回

形狀縮圖。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
傳回形狀縮圖。

### 返回

若使用 ShapeThumbnailBounds.Appearance 且形狀沒有可見元素，則傳回形狀縮圖或 None。


```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds) | 形狀縮圖邊界類型。 |
| scale_x | **float** | X 比例 |
| scale_y | **float** | Y 比例 |



### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`Ink`](/slides/python-net/zh-hant/aspose.slides.ink/ink)
* 列舉 [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds)
* 模組 [`aspose.slides.ink`](/slides/python-net/zh-hant/aspose.slides.ink)
* 函式庫 [`Aspose.Slides`](/slides/python-net)