---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides 的 Java API 參考
description: 從 Pptx 文字提取 HTML 的選項。
type: docs
url: /zh-hant/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

從 Pptx 文字提取 HTML 的選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 取得或設定值，指示是否應新增 Clipboard 標頭。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 取得或設定值，指示是否應新增 Clipboard 標頭。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 取得或設定文字屬性的繼承深度。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 取得或設定文字屬性的繼承深度。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 取得或設定回呼物件，以控制外部物件的儲存方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 取得或設定回呼物件，以控制外部物件的儲存方式。 |
| [getEncodingName()](#getEncodingName--) | 取得或設定 html 編碼名稱。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 取得或設定 html 編碼名稱。 |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

取得或設定值，指示是否應新增 Clipboard 標頭。讀/寫 boolean.

**返回：**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

取得或設定值，指示是否應新增 Clipboard 標頭。讀/寫 boolean.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

取得或設定文字屬性的繼承深度。讀/寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**返回：**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

取得或設定文字屬性的繼承深度。讀/寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

取得或設定回呼物件，以控制外部物件的儲存方式。讀/寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**返回：**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

取得或設定回呼物件，以控制外部物件的儲存方式。讀/寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

取得或設定 html 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。讀/寫 String。

**返回：**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

取得或設定 html 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。讀/寫 String。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |