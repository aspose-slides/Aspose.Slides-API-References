---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController 類別

控制 HTML 檔案的產生。

IHtmlFormattingController 類型公開以下成員：

## 方法

| 方法 | 說明 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | 用於寫入 HTML 文件標頭。於每次簡報轉換時呼叫一次。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | 用於寫入 HTML 文件頁尾。於每次簡報轉換時呼叫一次。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | 用於寫入 HTML 投影片標頭。於每張投影片呼叫一次。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | 用於寫入 HTML 投影片頁尾。於每張投影片呼叫一次。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | 在形狀渲染之前呼叫。於每個形狀呼叫一次。如果此函式向產生器寫入任何內容，則目前投影片影像的產生將完成，插入已加入的 HTML 片段，並在先前的影像上方開始產生新影像。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | 在形狀渲染之前呼叫。於每個形狀呼叫一次。如果此函式向產生器寫入任何內容，則目前投影片影像的產生將完成，插入已加入的 HTML 片段，並在先前的影像上方開始產生新影像。 |

### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)