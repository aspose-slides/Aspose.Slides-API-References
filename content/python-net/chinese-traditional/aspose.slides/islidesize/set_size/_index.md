---
title: set_size method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
根據類型設定投影片大小，並縮放現有內容。

```python
def set_size(self, type, scale_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/zh-hant/aspose.slides/slidesizetype) | 要套用的預定義投影片大小。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype) | 要使用的內容縮放模式。 |

### 備註

指派除 [`SlideSizeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/slidesizetype/CUSTOM) 之外的任何值，都會根據所選類型調整 [`ISlideSize.size`](/slides/python-net/zh-hant/aspose.slides/islidesize/size)
            同時保留 [`ISlideSize.orientation`](/slides/python-net/zh-hant/aspose.slides/islidesize/orientation)。

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
明確設定投影片尺寸，並縮放現有內容。

```python
def set_size(self, width, height, scale_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| width | **float** | 新投影片寬度（單位：點）。 |
| height | **float** | 新投影片高度（單位：點）。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype) | 要使用的內容縮放模式。 |

### 備註

這會將 [`ISlideSize.type`](/slides/python-net/zh-hant/aspose.slides/islidesize/type) 屬性重設為 [`SlideSizeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/slidesizetype/CUSTOM)
            並設定 [`ISlideSize.orientation`](/slides/python-net/zh-hant/aspose.slides/islidesize/orientation)。

### 另見
* 類別 [`ISlideSize`](/slides/python-net/zh-hant/aspose.slides/islidesize)
* 列舉 [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype)
* 列舉 [`SlideSizeType`](/slides/python-net/zh-hant/aspose.slides/slidesizetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)