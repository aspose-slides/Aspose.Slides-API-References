---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
weight: 569
url: /java/com.aspose.slides/texttohtmlconversionoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Options for extracting HTML from the Pptx text.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returns or sets value, indicating if Clipboard headers should be added. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returns or sets value, indicating if Clipboard headers should be added. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returns or sets inhering depth for text properties. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returns or sets inhering depth for text properties. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returns or sets a callback object which controlls how external object will be stored. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returns or sets a callback object which controlls how external object will be stored. |
| [getEncodingName()](#getEncodingName--) | Returns or sets html encoding name. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returns or sets html encoding name. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Returns or sets value, indicating if Clipboard headers should be added. Read/write boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Returns or sets value, indicating if Clipboard headers should be added. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Returns or sets inhering depth for text properties. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Returns or sets inhering depth for text properties. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Returns or sets a callback object which controlls how external object will be stored. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Returns or sets a callback object which controlls how external object will be stored. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Returns or sets html encoding name. This value will be saved to the generated HTML file, but its up to caller to ensure that file will be saved in this encoding. Read/write String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Returns or sets html encoding name. This value will be saved to the generated HTML file, but its up to caller to ensure that file will be saved in this encoding. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

