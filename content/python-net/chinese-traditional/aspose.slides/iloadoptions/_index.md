---
title: ILoadOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iloadoptions/
---
## ILoadOptions 類別

允許在載入簡報時指定其他選項（例如格式或預設字型）。

ILoadOptions 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/load_format/) | Returns or sets format of a presentation to load.<br/>            讀寫 [`LoadFormat`](/slides/python-net/zh-hant/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/default_regular_font/) | Returns or sets Regular font used in case source font is not found.<br/>            讀寫 **str**. |
| [`default_symbol_font`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/default_symbol_font/) | Returns or sets Symbol font used in case source font is not found.<br/>            讀寫 **str**. |
| [`default_asian_font`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/default_asian_font/) | Returns or sets Asian font used in case source font is not found.<br/>            讀寫 **str**. |
| [`password`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/password/) | Gets or sets the password.<br/>            讀寫 **str**. |
| [`only_load_document_properties`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/only_load_document_properties/) | This property makes sense, if presentation file is password protected.<br/>            Value of true means that only document properties must be loaded from an encrypted <br/>            presentation file and password must be ignored.<br/>            Value of false means that entire encrypted presentation must be loaded with use of right <br/>            password.<br/>            If presentation isn't encrypted then property value is always ignored.<br/>            If document properties of an encrypted file aren't public and property value is true then<br/>            document properties cannot be loaded and exception will be thrown.<br/>            讀寫 **bool**. |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/warning_callback/) | Returns or sets an object which receives warnings and decides whether loading <br/>            process will continue or will be aborted.<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/blob_management_options/) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior,<br/>            such as using of temporary files or max BLOBs bytes in memory. These options intended to set up<br/>            the best performance/memory consumption ratio for a perticular environment or requirements.<br/>            A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can <br/>            be an audio, video or presentation itself. |
| [`document_level_font_sources`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/document_level_font_sources/) | Specifies sources for external fonts to be used by the presentation.<br/>            These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [`interruption_token`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/interruption_token/) | The token to monitor for interruption requests.<br/>            <br/>            This token manages the whole [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as presentaion <br/>            loading or saving, will be interrupted via calling of the [`IInterruptionTokenSource.interrupt`](/slides/python-net/zh-hant/aspose.slides/iinterruptiontokensource/interrupt) method of <br/>            the [`IInterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/resource_loading_callback/) | Returns or sets callback interface which manages external resources loading.<br/>            讀寫 [`IResourceLoadingCallback`](/slides/python-net/zh-hant/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/spreadsheet_options/) | Represents options which can be used to specify additional spreadsheets behavior. |
| [`default_text_language`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/default_text_language/) | Returns or sets the default language for presentation text.<br/>             讀寫 **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/zh-hant/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.<br/>            <br/>The types of the embedded binary objects:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/zh-hant/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            讀寫 **bool**. |


### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)