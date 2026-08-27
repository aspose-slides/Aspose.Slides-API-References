---
title: Audio
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/audio/
---
## Audio 类

 表示嵌入的音频文件。
 
### getBinaryData {#getBinaryData}

| 名称 | 描述 |
| --- | --- |
| getBinaryData () | 返回音频数据的副本。 如果数据量很大，请考虑使用 #getStream 方法，以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。 只读 byte[]. |

 **返回:**
byte


---


### getContentType {#getContentType}

| 名称 | 描述 |
| --- | --- |
| getContentType () | 返回音频的 MIME 类型，编码于 ( #getBinaryData)。 只读 String。 |

 **返回:**
String


---


### getStream {#getStream}

| 名称 | 描述 |
| --- | --- |
| getStream () | 返回用于读取的 Stream 流。 使用 'using' 或在使用后关闭流。 |

 **返回:**
InputStream


---


### setContentType {#setContentType}

| 名称 | 描述 |
| --- | --- |
| setContentType (String) | 返回音频的 MIME 类型，编码于 ( #getBinaryData)。 只读 String。 |

 **返回:**
void


---