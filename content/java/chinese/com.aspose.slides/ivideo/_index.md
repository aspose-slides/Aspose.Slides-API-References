---
title: IVideo
second_title: Aspose.Slides Java API 参考
description: 表示嵌入到演示文稿中的视频。
type: docs
url: /zh/com.aspose.slides/ivideo/
---```
public interface IVideo
```

表示嵌入到演示文稿中的视频。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentType()](#getContentType--) | 返回视频的 MIME 类型，已在（\#getBinaryData.getBinaryData）中编码。 |
| [getBinaryData()](#getBinaryData--) | 返回音频数据的副本。 |
| [getStream()](#getStream--) | 返回用于读取的 Stream 流。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


返回视频的 MIME 类型，已在（\#getBinaryData.getBinaryData）中编码。只读 String。

**返回：**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


返回音频数据的副本。对于大量数据，建议使用 \#getStream.getStream 方法，以防止不必要地将视频数据加载到内存中，甚至导致 OutOfMemoryException。只读 byte[]。

**返回：**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


返回用于读取的 Stream 流。使用 `using` 或在使用后关闭流。

**返回：**
java.io.InputStream - 用于读取的流。