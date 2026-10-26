---
title: Audio
second_title: Aspose.Slides for Android via Java API 参考
description: 表示嵌入的音频文件。
type: docs
url: /zh/com.aspose.slides/audio/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

表示嵌入的音频文件。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentType()](#getContentType--) | 返回音频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 返回音频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。 |
| [getBinaryData()](#getBinaryData--) | 返回音频数据的副本。 |
| [getStream()](#getStream--) | 返回用于读取的 Stream 流。 |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

返回音频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。只读 String。

**返回:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

返回音频的 MIME 类型，已在 (\#getBinaryData.getBinaryData) 中编码。只读 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

返回音频数据的副本。对于大量数据，建议使用 \#getStream.getStream 方法，以避免不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。只读 byte[]。

**返回:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

返回用于读取的 Stream 流。使用完毕后请使用 `using` 或手动关闭流。

**返回:**  
java.io.InputStream - 用于读取的流。