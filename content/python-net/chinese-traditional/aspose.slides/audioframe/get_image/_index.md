---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
返回 shape 縮圖。
            ShapeThumbnailBounds.Shape shape 縮圖邊界類型預設使用。

### 返回
Shape 縮圖。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回 shape 縮圖。

### 返回
在使用 ShapeThumbnailBounds.Appearance 且 shape 沒有可見元素時，返回 shape 縮圖或 None。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds) | shape 縮圖邊界類型。 |
| scale_x | **float** | X 比例 |
| scale_y | **float** | Y 比例 |

### 另請參閱
* class [`AudioFrame`](/slides/python-net/zh-hant/aspose.slides/audioframe)
* class [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)