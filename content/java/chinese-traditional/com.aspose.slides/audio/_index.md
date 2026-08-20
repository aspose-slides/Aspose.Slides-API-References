---
title: Audio
second_title: Aspose.Slides for Java API 參考
description: 代表嵌入式音訊檔案。
type: docs
url: /zh-hant/com.aspose.slides/audio/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

代表嵌入式音訊檔案。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getContentType()](#getContentType--) | 返回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 返回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 |
| [getBinaryData()](#getBinaryData--) | 返回音訊資料的副本。 |
| [getStream()](#getStream--) | 返回用於讀取的 Stream 串流。 |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

返回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 唯讀 String。

**返回：**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

返回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 唯讀 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

返回音訊資料的副本。 若資料量很大，建議使用 \#getStream.getStream 方法，以避免不必要地將音訊資料載入記憶體，甚至導致 OutOfMemoryException。 唯讀 byte[]。

**返回：**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

返回用於讀取的 Stream 串流。 使用 'using' 或在使用後關閉串流。

**返回：**
java.io.InputStream - 用於讀取的 Stream。