---
title: Audio
second_title: Aspose.Slides for Android via Java API 參考
description: 表示嵌入的音訊檔案。
type: docs
url: /zh-hant/com.aspose.slides/audio/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

表示嵌入的音訊檔案。

## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | 傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 |
| [getBinaryData()](#getBinaryData--) | 傳回音訊資料的副本。 |
| [getStream()](#getStream--) | 傳回供讀取的 Stream。 |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。唯讀 String。

**Returns:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。唯讀 String。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

傳回音訊資料的副本。若資料量龐大，建議使用 \#getStream.getStream 方法以防止不必要的音訊資料載入記憶體或甚至 OutOfMemoryException。唯讀 byte[]。

**Returns:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

傳回供讀取的 Stream。使用 'using' 或在使用後關閉串流。

**Returns:**  
java.io.InputStream - 用於讀取的串流。