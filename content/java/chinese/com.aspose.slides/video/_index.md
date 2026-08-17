---
title: Video
second_title: Aspose.Slides for Java API 参考
description: 表示嵌入到演示文稿中的图像。
type: docs
url: /zh/com.aspose.slides/video/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

表示嵌入到演示文稿中的图像。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentType()](#getContentType--) | 返回视频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。 |
| [getBinaryData()](#getBinaryData--) | 返回音频数据的副本。 |
| [getStream()](#getStream--) | 返回用于读取的 Stream 流。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


返回视频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。只读 String。

**返回：**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


返回音频数据的副本。对于大量数据，建议使用 \#getStream.getStream 方法，以防止不必要地将视频数据加载到内存中，甚至导致 OutOfMemoryException。只读 byte[]。

**返回：**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


返回用于读取的 Stream 流。使用 'using' 或在使用后关闭流。

**返回：**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject