---
title: Compress class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/compress/
---
## Compress 類別

代表一組旨在壓縮 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 的方法。

Compress 類型公開以下成員：

## 方法

| 方法 | 描述 |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress/compress_presentation/#presentation) | 透過套用所有可用的壓縮步驟來減少簡報的大小：<br/>            <br/>* 移除未使用的母片投影片 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* 移除未使用的版面配置投影片 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* 只保留嵌入字型中實際使用的字形 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* 將圖片解析度降低至 150 DPI，並刪除圖片的裁剪區域 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | 透過移除未使用的母片投影片來壓縮 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)。 |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | 透過移除未使用的版面配置投影片來壓縮 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)。 |
| [`compress_embedded_fonts(pres)`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | 透過從嵌入字型中移除未使用的字元來壓縮 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)。 |
| [`compress_images(presentation, resolution)`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | 降低簡報中圖片的解析度並刪除其裁剪區域，<br/>            類似於對所有圖片套用 PowerPoint 的「壓縮圖片」功能。<br/>            會處理投影片、版面配置投影片及母片投影片上的圖片，包括群組圖形內的圖片<br/>            以及圖形的圖片填充。 |


### 另見
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)