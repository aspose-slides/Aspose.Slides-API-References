---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: 代表 WebVTT 隱藏式字幕。
type: docs
url: /zh-hant/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

代表 WebVTT 隱藏式字幕。
## Methods

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 返回封閉式字幕的全域唯一識別碼 (GUID)。 |
| [getLabel()](#getLabel--) | 返回或設定封閉式字幕的標籤。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 返回或設定封閉式字幕的標籤。 |
| [getBinaryData()](#getBinaryData--) | 返回封閉式字幕的二進位資料。 |
| [getDataAsString()](#getDataAsString--) | 返回封閉式字幕資料，以 UTF-8 編碼的字串形式。唯讀 String。 |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


返回封閉式字幕的全域唯一識別碼 (GUID)。唯讀 java.util.UUID。

**Returns:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


返回或設定封閉式字幕的標籤。可讀寫 String。

**Returns:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


返回或設定封閉式字幕的標籤。可讀寫 String。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


返回封閉式字幕的二進位資料。唯讀 byte[]。

**Returns:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


返回封閉式字幕資料，以 UTF-8 編碼的字串形式。唯讀 String。

**Returns:**
java.lang.String