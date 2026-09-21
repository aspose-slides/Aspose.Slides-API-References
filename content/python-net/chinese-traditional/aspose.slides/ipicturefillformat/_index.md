---
title: IPictureFillFormat class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat 類別

Represents a picture fill style.

The IPictureFillFormat type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/dpi/) | 傳回或設定用於填充圖片的 dpi。<br/>            讀寫 **int**. |
| [`picture_fill_mode`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/picture_fill_mode/) | 傳回或設定圖片填充模式。<br/>            讀寫 [`PictureFillMode`](/slides/python-net/zh-hant/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/picture/) | 傳回圖片。<br/>            唯讀 [`ISlidesPicture`](/slides/python-net/zh-hant/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/crop_left/) | 傳回或設定圖片左側裁剪掉的實際圖像寬度百分比數。<br/>            讀寫 **float**. |
| [`crop_top`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/crop_top/) | 傳回或設定圖片上方裁剪掉的實際圖像高度百分比數。<br/>            讀寫 **float**. |
| [`crop_right`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/crop_right/) | 傳回或設定圖片右側裁剪掉的實際圖像寬度百分比數。<br/>            讀寫 **float**. |
| [`crop_bottom`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/crop_bottom/) | 傳回或設定圖片底部裁剪掉的實際圖像高度百分比數。<br/>            讀寫 **float**. |
| [`stretch_offset_left`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/stretch_offset_left/) | 傳回或設定由相對於形狀邊界框左邊緣的百分比偏移定義的填充矩形左邊緣。正百分比表示內縮，負百分比表示外伸。<br/>            讀寫 **float**. |
| [`stretch_offset_top`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/stretch_offset_top/) | 傳回或設定由相對於形狀邊界框上邊緣的百分比偏移定義的填充矩形上邊緣。正百分比表示內縮，負百分比表示外伸。<br/>            讀寫 **float**. |
| [`stretch_offset_right`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/stretch_offset_right/) | 傳回或設定由相對於形狀邊界框右邊緣的百分比偏移定義的填充矩形右邊緣。正百分比表示內縮，負百分比表示外伸。<br/>            讀寫 **float**. |
| [`stretch_offset_bottom`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | 傳回或設定由相對於形狀邊界框底邊緣的百分比偏移定義的填充矩形底邊緣。正百分比表示內縮，負百分比表示外伸。<br/>            讀寫 **float**. |
| [`tile_offset_x`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_offset_x/) | 傳回或設定紋理相對於形狀原點的水平偏移（單位為點）。正值將紋理向右移動，負值則向左移動。<br/>            讀寫 **float**. |
| [`tile_offset_y`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_offset_y/) | 傳回或設定紋理相對於形狀原點的垂直偏移（單位為點）。正值將紋理向下移動，負值則向上移動。<br/>            讀寫 **float**. |
| [`tile_scale_x`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_scale_x/) | 傳回或設定紋理填充的水平縮放比例（以百分比表示）。<br/>            讀寫 **float**. |
| [`tile_scale_y`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_scale_y/) | 傳回或設定紋理填充的垂直縮放比例（以百分比表示）。<br/>            讀寫 **float**. |
| [`tile_alignment`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_alignment/) | 傳回或設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及其在形狀上的重複方式。<br/>            讀寫 [`RectangleAlignment`](/slides/python-net/zh-hant/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/tile_flip/) | 傳回或設定紋理圖塊沿水平、垂直或兩個軸翻轉。<br/>            讀寫 [`TileFlip`](/slides/python-net/zh-hant/aspose.slides/tileflip). |

## 方法

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | 依據形狀大小與指定的解析度壓縮影像以縮小其尺寸。可選地，同時刪除裁剪區域。 |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/compress_image/#bool-float) | 依據形狀大小與指定的解析度壓縮影像以縮小其尺寸。可選地，同時刪除裁剪區域。 |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | 刪除填充圖片的裁剪區域。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)