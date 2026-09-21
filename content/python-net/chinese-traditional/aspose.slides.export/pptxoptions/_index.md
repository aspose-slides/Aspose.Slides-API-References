---
title: PptxOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pptxoptions/
---
## PptxOptions 類別

表示用於儲存 OpenXml 簡報的選項 (PPTX, PPSX, POTX, PPTM, PPSM, POTM)。

**繼承:**[`PptxOptions`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

PptxOptions 型別公開以下成員：

## 建構函式

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/__init__/#) | 建立 PptxOptions 的新實例 |

## 屬性

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/warning_callback/) | 取得或設定一個接收警告並決定載入程序是否繼續或中止的物件。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/progress_callback/) | 代表一個以百分比提供儲存進度更新的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/default_regular_font/) | 取得或設定在找不到來源字型時使用的字型。<br/>            讀寫 **str**. |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/gradient_style/) | 取得或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。 <br/>            讀寫 **bool**。 預設值為 **false** . |
| [`conformance`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/conformance/) | 指定簡報文件符合的相容等級。<br/>            預設值為 [`Conformance.ECMA_376_2006`](/slides/python-net/zh-hant/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/zip_64_mode/) | 指定簡報文件是否使用 ZIP64 格式。 <br/>            預設值為 [`Zip64Mode.IF_NECESSARY`](/slides/python-net/zh-hant/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/refresh_thumbnail/) | 指定是否重新整理簡報的縮圖。 <br/>            讀寫 **bool**。<br/>            預設值為 **true** . |
| [`compression_level`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions/compression_level/) | 指定儲存簡報文件時使用的壓縮等級。<br/>            預設值為 [`CompressionLevel.LEVEL6`](/slides/python-net/zh-hant/aspose.slides.export/compressionlevel/LEVEL6). |

### 另請參閱
* 類別 [`PptxOptions`](/slides/python-net/zh-hant/aspose.slides.export/pptxoptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)