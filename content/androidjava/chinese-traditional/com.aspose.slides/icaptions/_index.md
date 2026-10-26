---
title: ICaptions
second_title: Aspose.Slides for Android Java API 參考
description: 表示 WebVTT 隱藏式字幕。
type: docs
url: /zh-hant/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

表示 WebVTT 隱藏式字幕。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 返回隱藏式字幕的全域唯一識別碼 (GUID)。 |
| [getLabel()](#getLabel--) | 返回或設定隱藏式字幕的標籤。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 返回或設定隱藏式字幕的標籤。 |
| [getBinaryData()](#getBinaryData--) | 返回隱藏式字幕的二進位資料。 |
| [getDataAsString()](#getDataAsString--) | 以 UTF-8 編碼的字串形式返回隱藏式字幕資料，唯讀 String。 |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

返回隱藏式字幕的全域唯一識別碼 (GUID)。唯讀 java.util.UUID。

**返回:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

返回或設定隱藏式字幕的標籤。可讀寫 String。

**返回:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

返回或設定隱藏式字幕的標籤。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

返回隱藏式字幕的二進位資料。唯讀 byte[]。

**返回:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

以 UTF-8 編碼的字串形式返回隱藏式字幕資料，唯讀 String。

**返回:**
java.lang.String