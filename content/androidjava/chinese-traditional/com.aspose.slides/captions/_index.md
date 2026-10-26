---
title: Captions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 WebVTT 閉字字幕。
type: docs
url: /zh-hant/com.aspose.slides/captions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

表示 WebVTT 閉字字幕。

## 方法

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 傳回閉字字幕的全域唯一識別碼 (GUID)。 |
| [getLabel()](#getLabel--) | 傳回或設定閉字字幕的標籤。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 傳回或設定閉字字幕的標籤。 |
| [getBinaryData()](#getBinaryData--) | 傳回閉字字幕的二進位資料。 |
| [getDataAsString()](#getDataAsString--) | 傳回閉字字幕資料，以 UTF-8 編碼的字串。唯讀 String。 |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

傳回閉字字幕的全域唯一識別碼 (GUID)。唯讀 java.util.UUID。

**傳回：**
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

傳回或設定閉字字幕的標籤。讀寫 String。

**傳回：**
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

傳回或設定閉字字幕的標籤。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

傳回閉字字幕的二進位資料。唯讀 byte[]。

**傳回：**
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

傳回閉字字幕資料，以 UTF-8 編碼的字串。唯讀 String。

**傳回：**
java.lang.String