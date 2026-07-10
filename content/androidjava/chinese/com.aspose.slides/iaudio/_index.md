---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: 表示嵌入的音频文件。
type: docs
url: /zh/com.aspose.slides/iaudio/
---```
public interface IAudio
```

表示嵌入的音频文件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an audio, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


返回音频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。只读 String。

**返回:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


返回音频数据的副本。对于大量数据的情况，建议使用 \#getStream.getStream 方法，以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。只读 byte[]。

**返回:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


返回用于读取的 Stream 流。使用 'using' 或在使用后关闭流。

**返回:**  
java.io.InputStream - 用于读取的流。