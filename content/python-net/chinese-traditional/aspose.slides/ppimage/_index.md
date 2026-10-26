---
title: PPImage class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ppimage/
---
## PPImage 類別

表示簡報中的圖像。

PPImage 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/zh-hant/aspose.slides/ppimage/binary_data/) | 返回圖像資料的副本。<br/>            唯讀 **int**[]. |
| [`image`](/slides/python-net/zh-hant/aspose.slides/ppimage/image/) | 返回圖像的副本。<br/>            唯讀 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/zh-hant/aspose.slides/ppimage/svg_image/) | 返回或設定 ISvgImage 物件 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/ppimage/content_type/) | 返回圖像的 MIME 類型，編碼為 [`PPImage.binary_data`](/slides/python-net/zh-hant/aspose.slides/ppimage/binary_data)。<br/>            唯讀 **str**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/ppimage/width/) | 返回圖像的寬度。<br/>            唯讀 **int**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/ppimage/height/) | 返回圖像的高度。<br/>            唯讀 **int**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/ppimage/x/) | 返回圖像的 X 偏移。<br/>            唯讀 **int**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/ppimage/y/) | 返回圖像的 Y 偏移。<br/>            唯讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/zh-hant/aspose.slides/ppimage/replace_image/#bytes) | 取代圖像資料。<br/>            新圖像的資料。當 newImageData 參數為 None 時。 |
| [`replace_image(self, new_image)`](/slides/python-net/zh-hant/aspose.slides/ppimage/replace_image/#iimage) | 取代圖像資料。注意：當 Image 為中繪圖檔時，將被光柵化。請改用 ReplaceImage(byte[])。<br/>            新圖像。當 newImage 參數為 None 時。 |
| [`replace_image(self, new_image)`](/slides/python-net/zh-hant/aspose.slides/ppimage/replace_image/#ippimage) | 取代圖像資料。<br/>            新的 IPPImage。當 newImage 參數為 None 時。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)