---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: 表示嵌入的音頻檔案。
type: docs
url: /zh-hant/com.aspose.slides/iaudio/
---```
public interface IAudio
```

表示嵌入的音頻檔案。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getContentType()](#getContentType--) | 返回音頻的 MIME 類型，已在 (\#getBinaryData.getBinaryData) 中編碼。 |
| [getBinaryData()](#getBinaryData--) | 返回音頻資料的副本。 |
| [getStream()](#getStream--) | 返回用於讀取的 Stream 流。 |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

返回音頻的 MIME 類型，已在 (\#getBinaryData.getBinaryData) 中編碼。唯讀 String。

**返回:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

返回音頻資料的副本。若資料量較大，建議使用 \#getStream.getStream 方法，以避免不必要將音頻資料載入記憶體或導致 OutOfMemoryException。唯讀 byte[]。

**返回:**  
byte[]

### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

返回用於讀取的 Stream 流。使用 'using' 或在使用後關閉串流。

**返回:**  
java.io.InputStream - 用於讀取的 Stream.