---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Java API 參考
description: 從 Pptx 文字提取 HTML 的選項。
type: docs
url: /zh-hant/com.aspose.slides/texttohtmlconversionoptions/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

從 Pptx 文字提取 HTML 的選項。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 傳回或設定 value，指示是否應新增 Clipboard 標頭。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 傳回或設定 value，指示是否應新增 Clipboard 標頭。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 傳回或設定繼承深度，用於文字屬性。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 傳回或設定繼承深度，用於文字屬性。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 傳回或設定回呼物件，以控制外部物件的儲存方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 傳回或設定回呼物件，以控制外部物件的儲存方式。 |
| [getEncodingName()](#getEncodingName--) | 傳回或設定 html 編碼名稱。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 傳回或設定 html 編碼名稱。 |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


傳回或設定 value，指示是否應新增 Clipboard 標頭。 可讀寫 boolean。

**傳回值：**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


傳回或設定 value，指示是否應新增 Clipboard 標頭。 可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


傳回或設定繼承深度，用於文字屬性。 可讀寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**傳回值：**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


傳回或設定繼承深度，用於文字屬性。 可讀寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


傳回或設定回呼物件，以控制外部物件的儲存方式。 可讀寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**傳回值：**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


傳回或設定回呼物件，以控制外部物件的儲存方式。 可讀寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


傳回或設定 html 編碼名稱。 此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。 可讀寫 String。

**傳回值：**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


傳回或設定 html 編碼名稱。 此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。 可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |