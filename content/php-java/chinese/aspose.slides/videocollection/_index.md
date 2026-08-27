---
title: VideoCollection
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/videocollection/
---
## VideoCollection 类

 表示 Video 对象的集合。
 
### addVideo {#addVideo}}

| 名称 | 描述 |
| --- | --- |
| addVideo ([Video](../video)) | 从另一个演示文稿添加视频文件的副本。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| video | [Video](../video) | 源视频。 |

 **返回值：**
[Video](../video)


---


### addVideo {#addVideo}}

| 名称 | 描述 |
| --- | --- |
| addVideo (InputStream, int) | 从流创建并添加视频到演示文稿。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 用于添加视频文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

 **返回值：**
[Video](../video)


---


### addVideo {#addVideo}}

| 名称 | 描述 |
| --- | --- |
| addVideo (byte[]) | 从字节数组创建并添加视频到演示文稿。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| videoData | byte[] | 视频字节。 |

 **返回值：**
[Video](../video)


---


### getSyncRoot {#getSyncRoot}}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回一个同步根。只读 Object。 |

 **返回值：**
Object


---


### get_Item {#get_Item}}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 IVideo。 |

 **返回值：**
[Video](../video)


---


### isSynchronized {#isSynchronized}}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个指示是否同步访问集合（线程安全）的值。只读 boolean。 |

 **返回值：**
boolean


---


### iterator {#iterator}}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回值：**



---


### iteratorJava {#iteratorJava}}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值：**



---


### size {#size}}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中视频文件的数量。只读 int。 |

 **返回值：**
int


---