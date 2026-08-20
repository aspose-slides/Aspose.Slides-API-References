---
title: Video
second_title: Aspose.Slides for Java API 參考
description: 代表嵌入於簡報中的影像。
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

代表嵌入於簡報中的影像。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentType()](#getContentType--) | 傳回影片的 MIME 類型，已在 (\#getBinaryData.getBinaryData) 中編碼。 |
| [getBinaryData()](#getBinaryData--) | 傳回音訊資料的副本。 |
| [getStream()](#getStream--) | 傳回用於讀取的 Stream 串流。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

傳回影片的 MIME 類型，已在 (\#getBinaryData.getBinaryData) 中編碼。唯讀 String.

**傳回：**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

傳回音訊資料的副本。若資料量龐大，請考慮使用 \#getStream.getStream 方法以避免將影片資料全部載入記憶體，甚至導致 OutOfMemoryException。唯讀 byte[]。

**傳回：**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

傳回用於讀取的 Stream 串流。使用 'using' 或在使用後關閉串流。

**傳回：**
java.io.InputStream - 用於讀取的串流。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject