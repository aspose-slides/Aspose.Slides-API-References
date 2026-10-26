---
title: PptOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pptoptions/
---
## PptOptions class

提供控制簡報以 PPT 格式儲存方式的選項。

**Inheritance:**[`PptOptions`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

PptOptions 類型公開以下成員：

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/__init__/#) |  |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/warning_callback/) | 取得或設定接收警告並決定載入程序是否繼續或中止的物件。<br/>            Read/write [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/progress_callback/) | 代表以百分比表示儲存進度更新的回呼物件。<br/>            See [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/default_regular_font/) | 取得或設定當找不到來源字型時使用的字型。<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/gradient_style/) | 取得或設定漸層的視覺樣式。<br/>            Read/write [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。<br/>            Read/write **bool**. 預設值為 **false** 。 |
| [`root_directory_clsid`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions/root_directory_clsid/) | 代表儲存在根目錄項目的物件類別 GUID (CLSID)。可用於 COM<br/>            啟動文件的應用程式。<br/>            預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。 |


### See Also
* 類別 [`PptOptions`](/slides/python-net/zh-hant/aspose.slides.export/pptoptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)