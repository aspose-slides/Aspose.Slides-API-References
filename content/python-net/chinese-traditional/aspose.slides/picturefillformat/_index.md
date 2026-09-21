---
title: PictureFillFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/picturefillformat/
---
## PictureFillFormat 類別

表示圖片填充樣式。

**繼承：**[`PictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

PictureFillFormat 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`dpi`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/dpi/) | 返回或設定用於填充圖片的 dpi。<br/>            可讀寫 **int**. |
| [`picture_fill_mode`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/picture_fill_mode/) | 返回或設定圖片填充模式。<br/>            可讀寫 [`PictureFillMode`](/slides/python-net/zh-hant/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/picture/) | 返回圖片。<br/>            唯讀 [`ISlidesPicture`](/slides/python-net/zh-hant/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/crop_left/) | 返回或設定實際圖像寬度的百分比，表示從圖片左側裁剪的部分。<br/>            可讀寫 **float**. |
| [`crop_top`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/crop_top/) | 返回或設定實際圖像高度的百分比，表示從圖片頂部裁剪的部分。<br/>            可讀寫 **float**. |
| [`crop_right`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/crop_right/) | 返回或設定實際圖像寬度的百分比，表示從圖片右側裁剪的部分。<br/>            可讀寫 **float**. |
| [`crop_bottom`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/crop_bottom/) | 返回或設定實際圖像高度的百分比，表示從圖片底部裁剪的部分。<br/>            可讀寫 **float**. |
| [`stretch_offset_left`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/stretch_offset_left/) | 返回或設定填充矩形的左邊緣，該邊緣由相對於形狀邊界框左邊緣的百分比偏移定義。<br/>            正的百分比表示內縮，負的百分比表示外伸。<br/>            可讀寫 **float**. |
| [`stretch_offset_top`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/stretch_offset_top/) | 返回或設定填充矩形的上邊緣，該邊緣由相對於形狀邊界框上邊緣的百分比偏移定義。<br/>            正的百分比表示內縮，負的百分比表示外伸。<br/>            可讀寫 **float**. |
| [`stretch_offset_right`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/stretch_offset_right/) | 返回或設定填充矩形的右邊緣，該邊緣由相對於形狀邊界框右邊緣的百分比偏移定義。<br/>            正的百分比表示內縮，負的百分比表示外伸。<br/>            可讀寫 **float**. |
| [`stretch_offset_bottom`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/stretch_offset_bottom/) | 返回或設定填充矩形的底邊緣，該邊緣由相對於形狀邊界框底邊緣的百分比偏移定義。<br/>            正的百分比表示內縮，負的百分比表示外伸。<br/>            可讀寫 **float**. |
| [`tile_offset_x`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_offset_x/) | 返回或設定紋理相對於形狀原點的水平偏移（點）。<br/>            正值使紋理向右移動，負值使其向左移動。<br/>            可讀寫 **float**. |
| [`tile_offset_y`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_offset_y/) | 返回或設定紋理相對於形狀原點的垂直偏移（點）。<br/>            正值使紋理向下移動，負值使其向上移動。<br/>            可讀寫 **float**. |
| [`tile_scale_x`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_scale_x/) | 返回或設定紋理填充的水平縮放比例（百分比）。<br/>            可讀寫 **float**. |
| [`tile_scale_y`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_scale_y/) | 返回或設定紋理填充的垂直縮放比例（百分比）。<br/>            可讀寫 **float**. |
| [`tile_alignment`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_alignment/) | 返回或設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及其在形狀內的重複方式。<br/>            可讀寫 [`RectangleAlignment`](/slides/python-net/zh-hant/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/tile_flip/) | 翻轉紋理平鋪的水平、垂直或雙軸。<br/>            可讀寫 [`TileFlip`](/slides/python-net/zh-hant/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | 將圖像大小縮小（根據形狀大小和指定的解析度），以壓縮圖像。可選地，還會刪除裁剪區域。 |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/compress_image/#bool-float) | 將圖像大小縮小（根據形狀大小和指定的解析度），以壓縮圖像。可選地，還會刪除裁剪區域。 |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/zh-hant/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | 刪除填充圖片的裁剪區域。 |

### 另請參閱
* 類別 [`PictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/picturefillformat)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)