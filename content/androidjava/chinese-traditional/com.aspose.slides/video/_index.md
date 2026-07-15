---
title: Video
second_title: Aspose.Slides for Android via Java API 參考
description: 代表嵌入於簡報中的圖像。
type: docs
url: /zh-hant/com.aspose.slides/video/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

代表嵌入於簡報中的圖像。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getContentType()](#getContentType--) | 傳回已在 (\#getBinaryData.getBinaryData) 中編碼之影片的 MIME 類型。 |
| [getBinaryData()](#getBinaryData--) | 傳回音訊資料的副本。 |
| [getStream()](#getStream--) | 傳回用於讀取的 Stream。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


傳回已在 (\#getBinaryData.getBinaryData) 中編碼之影片的 MIME 類型。唯讀 String。

**傳回值:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


傳回音訊資料的副本。若資料量龐大，請考慮使用 \#getStream.getStream 方法，以避免不必要地將影片資料載入記憶體或導致 OutOfMemoryException。唯讀 byte[]。

**傳回值:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```


傳回用於讀取的 Stream。使用完畢後請使用 'using' 或關閉串流。

**傳回值:**  
java.io.InputStream - 用於讀取的串流。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值:**  
com.aspose.slides.IDOMObject