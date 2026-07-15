---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 從 Pptx 文字抽取 HTML 的選項。
type: docs
url: /zh-hant/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

從 Pptx 文字抽取 HTML 的選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 返回或設定值，指示是否應加入剪貼簿標頭。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 返回或設定值，指示是否應加入剪貼簿標頭。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 返回或設定文字屬性的繼承深度。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 返回或設定文字屬性的繼承深度。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 返回或設定回呼物件，以控制外部物件的儲存方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 返回或設定回呼物件，以控制外部物件的儲存方式。 |
| [getEncodingName()](#getEncodingName--) | 返回或設定 HTML 編碼名稱。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 返回或設定 HTML 編碼名稱。 |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


返回或設定值，指示是否應加入剪貼簿標頭。可讀寫 boolean。

**返回:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


返回或設定值，指示是否應加入剪貼簿標頭。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


返回或設定文字屬性的繼承深度。可讀寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**返回:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


返回或設定文字屬性的繼承深度。可讀寫 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


返回或設定回呼物件，以控制外部物件的儲存方式。可讀寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**返回:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


返回或設定回呼物件，以控制外部物件的儲存方式。可讀寫 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


返回或設定 HTML 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。可讀寫 String。

**返回:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


返回或設定 HTML 編碼名稱。此值將儲存至產生的 HTML 檔案，但由呼叫端確保檔案以此編碼儲存。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |