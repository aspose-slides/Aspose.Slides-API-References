---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 從 Pptx 文字提取 HTML 的選項。
type: docs
url: /zh-hant/com.aspose.slides/texttohtmlconversionoptions/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

從 Pptx 文字提取 HTML 的選項。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## 方法

| 方法 | 說明 |
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

取得或設定值，指示是否應該新增 Clipboard 標頭。讀/寫 boolean.

**回傳:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

取得或設定值，指示是否應該新增 Clipboard 標頭。讀/寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

取得或設定文字屬性的繼承深度。讀/寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**回傳:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

取得或設定文字屬性的繼承深度。讀/寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

取得或設定回呼物件，控制外部物件的儲存方式。讀/寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**回傳:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

取得或設定回呼物件，控制外部物件的儲存方式。讀/寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

取得或設定 HTML 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。讀/寫 String。

**回傳:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

取得或設定 HTML 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。讀/寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |