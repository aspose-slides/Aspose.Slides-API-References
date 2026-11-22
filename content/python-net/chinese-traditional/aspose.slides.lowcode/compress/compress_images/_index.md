---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
降低簡報中圖片的解析度並刪除其裁切區域，
            類似於在所有圖片上套用 PowerPoint 的「壓縮圖片」功能。
            會處理投影片、版面投影片和母片上的圖片，包含群組圖形內的圖片
            以及圖形的圖片填充。

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) | 要處理的簡報。 |
| resolution | [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression) | 目標解析度相對於每張圖片顯示時的尺寸。<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) 保持圖片不變。 |

### 備註

已在目標解析度或以下的圖片將保持不變；圖片絕不會被放大。

未處理的項目：投影片背景、表格儲存格填充、圖表、SmartArt、GIF 圖片（以保留動畫），
            SVG 和中繪圖檔（EMF/WMF）圖像。

裁切區域會永久移除，且無法在 PowerPoint 中復原。

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` 為 `None`。 |

### 另請參閱
* 類別 [`Compress`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 列舉 [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)