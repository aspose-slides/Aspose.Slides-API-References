---
title: Video
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/video/
---
## Video 类

 表示嵌入到演示文稿中的图像。
 
### getBinaryData {#getBinaryData}

| 名称 | 描述 |
| --- | --- |
| getBinaryData () | 返回音频数据的副本。如果数据量很大，考虑使用 #getStream 方法，以防止不必要地将视频的数据加载到内存中，甚至导致 OutOfMemoryException。只读 byte[]. |

 **返回：**
byte


---


### getContentType {#getContentType}

| 名称 | 描述 |
| --- | --- |
| getContentType () | 返回视频的 MIME 类型，该类型在（ #getBinaryData）中编码。只读 String。 |

 **返回：**
String


---


### getStream {#getStream}

| 名称 | 描述 |
| --- | --- |
| getStream () | 返回用于读取的 Stream 流。使用 'using' 或在使用后关闭流。 |

 **返回：**
InputStream


---