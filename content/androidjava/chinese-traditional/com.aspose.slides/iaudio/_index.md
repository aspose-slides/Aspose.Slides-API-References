---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /zh-hant/com.aspose.slides/iaudio/
---```
public interface IAudio
```

表示嵌入式音訊檔案。
## 方法

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | 傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。 |
| [getBinaryData()](#getBinaryData--) | 傳回音訊資料的副本。 |
| [getStream()](#getStream--) | 傳回用於讀取的 Stream stream。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


傳回音訊的 MIME 類型，編碼於 (\#getBinaryData.getBinaryData)。唯讀 String。

**傳回:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


傳回音訊資料的副本。若資料量龐大，建議使用 \#getStream.getStream 方法，以避免不必要地將音訊資料載入記憶體，甚至導致 OutOfMemoryException。唯讀 byte[]。

**傳回:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


傳回用於讀取的 Stream stream。使用 'using' 或在使用後關閉串流。

**傳回:**
java.io.InputStream - 用於讀取的串流。