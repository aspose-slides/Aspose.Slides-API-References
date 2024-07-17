---
title: LoadOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/loadoptions/
---


## LoadOptions class

Allows to specify additional options (such as format or default font) when loading a presentation.

The LoadOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__`](/slides/python-net/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Properties

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/aspose.slides/loadoptions/load_format/) | Returns or sets format of a presentation to load.<br/>            Read/write [`LoadFormat`](/slides/python-net/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/aspose.slides/loadoptions/default_regular_font/) | Returns or sets Regular font used in case source font is not found.<br/>            Read/write **str**. |
| [`default_symbol_font`](/slides/python-net/aspose.slides/loadoptions/default_symbol_font/) | Returns or sets Symbol font used in case source font is not found.<br/>            Read/write **str**. |
| [`default_asian_font`](/slides/python-net/aspose.slides/loadoptions/default_asian_font/) | Returns or sets Asian font used in case source font is not found.<br/>            Read/write **str**. |
| [`password`](/slides/python-net/aspose.slides/loadoptions/password/) | Gets or sets the password.<br/>            Read/write **str**. |
| [`only_load_document_properties`](/slides/python-net/aspose.slides/loadoptions/only_load_document_properties/) | This property makes sense, if presentation file is password protected.<br/>            Value of true means that only document properties must be loaded from an encrypted <br/>            presentation file and password must be ignored.<br/>            Value of false means that entire encrypted presentation must be loaded with use of right <br/>            password.<br/>            If presentation isn't encrypted then property value is always ignored.<br/>            If document properties of an encrypted file aren't public and property value is true then<br/>            document properties cannot be loaded and exception will be thrown.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/aspose.slides/loadoptions/warning_callback/) | Returns or sets an object which receives warnings and decides whether loading <br/>            process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/aspose.slides/loadoptions/blob_management_options/) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior,<br/>            such as using of temporary files or max BLOBs bytes in memory. These options intended to set up<br/>            the best performance/memory consumption ratio for a perticular environment or requirements.<br/>            A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can <br/>            be an audio, video or presentation itself. |
| [`document_level_font_sources`](/slides/python-net/aspose.slides/loadoptions/document_level_font_sources/) | Specifies sources for external fonts to be used by the presentation.<br/>            These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [`interruption_token`](/slides/python-net/aspose.slides/loadoptions/interruption_token/) | The token to monitor for interruption requests.<br/>            <br/>            This token manages the whole [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading <br/>            or saving of presentation, will be interrupted via calling of the [`InterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/interruptiontokensource/interrupt) method of <br/>            the [`InterruptionTokenSource`](/slides/python-net/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/aspose.slides/loadoptions/resource_loading_callback/) | Returns or sets callback interface which manages external resources loading.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/aspose.slides/loadoptions/spreadsheet_options/) | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |
| [`default_text_language`](/slides/python-net/aspose.slides/loadoptions/default_text_language/) | Returns or sets the default language for presentation text.<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.<br/>            <br/>The types of the embedded binary objects:<br/><br/>\|<br/>\|<br/>\|<br/>\|<br/>\|<br/><br/><br/>            Read/write **bool**. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

