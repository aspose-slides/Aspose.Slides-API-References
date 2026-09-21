---
title: set_size method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
依類型設定投影片大小，並縮放現有內容。

```python
def set_size(self, type, scale_type):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/zh-hant/aspose.slides/slidesizetype) | 要套用的預先定義投影片大小。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype) | 要使用的內容縮放模式。 |

### 備註

指派除 [`SlideSizeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/slidesizetype/CUSTOM) 之外的任何值時，會根據所選類型調整 [`SlideSize.size`](/slides/python-net/zh-hant/aspose.slides/slidesize/size)，同時保留 [`SlideSize.orientation`](/slides/python-net/zh-hant/aspose.slides/slidesize/orientation)。

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
明確設定投影片的寬度與高度，並縮放現有內容。

```python
def set_size(self, width, height, scale_type):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| width | **float** | 新投影片寬度（以點為單位）。 |
| height | **float** | 新投影片高度（以點為單位）。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype) | 要使用的內容縮放模式。 |

### 備註

這會將 [`SlideSize.type`](/slides/python-net/zh-hant/aspose.slides/slidesize/type) 屬性重設為 [`SlideSizeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/slidesizetype/CUSTOM)，並設定 [`SlideSize.orientation`](/slides/python-net/zh-hant/aspose.slides/slidesize/orientation)。

### 另請參閱
* 類別 [`SlideSize`](/slides/python-net/zh-hant/aspose.slides/slidesize)
* 列舉 [`SlideSizeScaleType`](/slides/python-net/zh-hant/aspose.slides/slidesizescaletype)
* 列舉 [`SlideSizeType`](/slides/python-net/zh-hant/aspose.slides/slidesizetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)