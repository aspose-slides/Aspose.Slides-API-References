---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController 類別

用於在 WOFF 格式中嵌入所有簡報字型的格式化控制器類別。

EmbedAllFontsHtmlController 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | 建立新的實例 |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | 建立新的實例 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | 呼叫以寫入 html 文件標頭。每次簡報轉換呼叫一次。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | 呼叫以寫入 html 文件頁腳。每次簡報轉換呼叫一次。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | 呼叫以寫入 html 投影片標頭。每張投影片呼叫一次。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | 呼叫以寫入 html 投影片頁腳。每張投影片呼叫一次。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | 在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片的影像產生將完成，加入的 html 片段會插入，且會在先前的影像上方開始產生新影像。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | 在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片的影像產生將完成，加入的 html 片段會插入，且會在先前的影像上方開始產生新影像。 |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | 寫入 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) 中包含的所有字型。 |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | 將資料以 base64 形式寫入 HTML 文件本身。 |


### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)