---
title: IVideo
second_title: Aspose.Slides for Java API 參考
description: 表示嵌入於簡報中的影片。
type: docs
url: /zh-hant/com.aspose.slides/ivideo/
---```
public interface IVideo
```

表示嵌入於簡報中的影片。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getContentType()](#getContentType--) | 傳回影片的 MIME 類型，已編碼於 (\#getBinaryData.getBinaryData)。 |
| [getBinaryData()](#getBinaryData--) | 傳回音訊資料的副本。 |
| [getStream()](#getStream--) | 傳回用於讀取的 Stream 流。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


傳回影片的 MIME 類型，已編碼於 (\#getBinaryData.getBinaryData)。唯讀 String.

**返回：**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


傳回音訊資料的副本。若資料量很大，請考慮使用 \#getStream.getStream 方法，以防止不必要地將影片資料載入記憶體，甚至導致 OutOfMemoryException。唯讀 byte[]。

**返回：**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


傳回用於讀取的 Stream 流。使用 'using' 或在使用後關閉流。

**返回：**
java.io.InputStream - 用於讀取的 Stream.