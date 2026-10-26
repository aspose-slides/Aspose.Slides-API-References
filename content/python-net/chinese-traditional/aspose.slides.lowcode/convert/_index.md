---
title: Convert class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/convert/
---
## Convert 類別

Represents a group of methods intended to convert [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation).

The Convert type exposes the following members:

## 方法

| 方法 | 描述 |
| :- | :- |
| [`to_pdf(pres_path, out_path)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_pdf/#str-str) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 PDF。 |
| [`to_pdf(pres_path, out_path, options)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_pdf/#str-str-asposeslidesexportipdfoptions) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 PDF。 |
| [`to_pdf(pres, out_path)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_pdf/#presentation-str) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 PDF。 |
| [`to_pdf(pres, out_path, options)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_pdf/#presentation-str-asposeslidesexportipdfoptions) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 PDF。 |
| [`to_svg(pres_path)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_svg/#str) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 SVG。 |
| [`to_svg(pres, options)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_svg/#presentation-asposeslidesexportisvgoptions) | 將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換為 SVG。 |
| [`to_jpeg(pres, output_file_name)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_jpeg/#presentation-str) | 將輸入的簡報轉換為一組 JPEG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.jpeg"，<br/>結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| [`to_jpeg(pres, output_file_name, image_size)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-asposeslidessize) | 將輸入的簡報轉換為一組 JPEG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.jpeg"，<br/>結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| [`to_jpeg(pres, output_file_name, scale, options)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-float-asposeslidesexportirenderingoptions) | 將輸入的簡報轉換為一組 JPEG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.jpeg"，<br/>結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| [`to_png(pres, output_file_name)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_png/#presentation-str) | 將輸入的簡報轉換為一組 PNG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.png"，<br/>結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| [`to_png(pres, output_file_name, image_size)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_png/#presentation-str-asposeslidessize) | 將輸入的簡報轉換為一組 PNG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.png"，<br/>結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| [`to_png(pres, output_file_name, scale, options)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_png/#presentation-str-float-asposeslidesexportirenderingoptions) | 將輸入的簡報轉換為一組 PNG 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.png"，<br/>結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| [`to_tiff(pres, output_file_name)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_tiff/#presentation-str) | 將輸入的簡報轉換為一組 TIFF 格式的影像。<br/>如果輸出檔名為 "myPath/myFilename.tiff"，<br/>結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。 |
| [`to_tiff(pres, output_file_name, options, multipage)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/to_tiff/#presentation-str-asposeslidesexportitiffoptions-bool) | 將輸入的簡報轉換為 TIFF 格式，並使用自訂選項。<br/>如果輸出檔名為 "myPath/myFilename.tiff" 且 `multipage` 為 `false`，<br/>結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。<br/>否則，若 `multipage` 為 `true`，結果將是一個多頁的 "myPath/myFilename.tiff" 文件。 |
| [`auto_by_extension(pres_path, out_path)`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert/auto_by_extension/#str-str) | 使用傳入的輸出路徑副檔名來判定所需的匯出格式，將 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 轉換。 |

### 另見
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)