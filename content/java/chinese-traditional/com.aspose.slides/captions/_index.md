---
title: Captions
second_title: Aspose.Slides for Java API 參考
description: 代表 WebVTT 關閉字幕。
type: docs
url: /zh-hant/com.aspose.slides/captions/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

代表 WebVTT 關閉字幕。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 傳回關閉字幕的全域唯一識別碼 (GUID)。 |
| [getLabel()](#getLabel--) | 傳回或設定關閉字幕的標籤。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 傳回或設定關閉字幕的標籤。 |
| [getBinaryData()](#getBinaryData--) | 傳回關閉字幕的二進位資料。 |
| [getDataAsString()](#getDataAsString--) | 傳回關閉字幕資料為 UTF-8 編碼字串。唯讀 String。 |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

傳回關閉字幕的全域唯一識別碼 (GUID)。唯讀 java.util.UUID。

**傳回：**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

傳回或設定關閉字幕的標籤。可讀寫 String。

**傳回：**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

傳回或設定關閉字幕的標籤。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

傳回關閉字幕的二進位資料。唯讀 byte[] 。

**傳回：**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

傳回關閉字幕資料為 UTF-8 編碼字串。唯讀 String。

**傳回：**
java.lang.String