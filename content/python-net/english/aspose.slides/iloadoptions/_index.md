---
title: ILoadOptions
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iloadoptions/
---


ILoadOptions class

Allows to specify additional options (such as format or default font) when loading a presentation.

The ILoadOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [load_format](/slides/python-net/aspose.slides/iloadoptions/load_format/) | Returns or sets format of a presentation to load.<br/>            Read/write <br/>[`LoadFormat`](/slides/python-net/aspose.slides/loadformat)<br/>. |
| [default_regular_font](/slides/python-net/aspose.slides/iloadoptions/default_regular_font/) | Returns or sets Regular font used in case source font is not found.<br/>            Read-write <br/>.NET type System.String<br/>. |
| [default_symbol_font](/slides/python-net/aspose.slides/iloadoptions/default_symbol_font/) | Returns or sets Symbol font used in case source font is not found.<br/>            Read-write <br/>.NET type System.String<br/>. |
| [default_asian_font](/slides/python-net/aspose.slides/iloadoptions/default_asian_font/) | Returns or sets Asian font used in case source font is not found.<br/>            Read-write <br/>.NET type System.String<br/>. |
| [password](/slides/python-net/aspose.slides/iloadoptions/password/) | Gets or sets the password.<br/>            Read-write <br/>.NET type System.String<br/>. |
| [only_load_document_properties](/slides/python-net/aspose.slides/iloadoptions/only_load_document_properties/) | This property makes sense, if presentation file is password protected.<br/>            Value of true means that only document properties must be loaded from an encrypted <br/>            presentation file and password must be ignored.<br/>            Value of false means that entire encrypted presentation must be loaded with use of right <br/>            password.<br/>            If presentation isn't encrypted then property value is always ignored.<br/>            If document properties of an encrypted file aren't public and property value is true then<br/>            document properties cannot be loaded and exception will be thrown.<br/>            Read-write <br/>.NET type System.Boolean<br/>. |
| [warning_callback](/slides/python-net/aspose.slides/iloadoptions/warning_callback/) | Returns or sets an object which receives warnings and decides whether loading <br/>            process will continue or will be aborted.<br/>            Read/write <br/>[`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback)<br/>. |
| [blob_management_options](/slides/python-net/aspose.slides/iloadoptions/blob_management_options/) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior,<br/>            such as using of temporary files or max BLOBs bytes in memory. These options intended to set up<br/>            the best performance/memory consumption ratio for a perticular environment or requirements.<br/>            <br/>A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can <br/>            be an audio, video or presentation itself. |
| [document_level_font_sources](/slides/python-net/aspose.slides/iloadoptions/document_level_font_sources/) | Specifies sources for external fonts to be used by the presentation.<br/>            These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [interruption_token](/slides/python-net/aspose.slides/iloadoptions/interruption_token/) | The token to monitor for interruption requests.<br/>            <br/><br/>            This token manages the whole <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/> instance lifetime. Any long-running operation, such as presentaion <br/>            loading or saving, will be interrupted via calling of the <br/>[`IInterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/iinterruptiontokensource/interrupt)<br/> method of <br/>            the <br/>[`IInterruptionTokenSource`](/slides/python-net/aspose.slides/iinterruptiontokensource)<br/>. |
| [resource_loading_callback](/slides/python-net/aspose.slides/iloadoptions/resource_loading_callback/) | Returns or sets callback interface which manages external resources loading.<br/>            Read/write <br/>[`IResourceLoadingCallback`](/slides/python-net/aspose.slides/iresourceloadingcallback)<br/>. |
| [spreadsheet_options](/slides/python-net/aspose.slides/iloadoptions/spreadsheet_options/) | Represents options which can be used to specify additional spreadsheets behavior. |
| [default_text_language](/slides/python-net/aspose.slides/iloadoptions/default_text_language/) | Returns or sets the default language for presentation text.<br/>             Read/write <br/>.NET type System.String<br/>. |

