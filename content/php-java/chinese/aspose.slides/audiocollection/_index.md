---
title: AudioCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/audiocollection/
---
## AudioCollection 类

表示嵌入式音频文件的集合。

### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio ([Audio](../audio)) | 从另一个演示文稿中添加音频文件的副本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| audio | [Audio](../audio) | 源音频。 |

**返回值：**
[Audio](../audio)

---


### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio (InputStream) | 从流中创建并添加音频到演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 用于添加音频的流。 |

**返回值：**
[Audio](../audio)

---


### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio (InputStream, int) | 从流中创建并添加音频到演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 用于添加视频音频的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回值：**
[Audio](../audio)

---


### addAudio {#addAudio}

| Name | Description |
| --- | --- |
| addAudio (byte[]) | 从字节数组创建并添加音频到演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| audioData | byte[] | 音频字节。 |

**返回值：**
[Audio](../audio)

---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回值：**
Object

---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 IAudio。 |

**返回值：**
[Audio](../audio)

---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

**返回值：**
boolean

---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

**返回值：**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回值：**



---


### size {#size}

| Name | Description |
| --- | --- |
| size () | 返回集合中音频文件的数量。只读 int。 |

**返回值：**
int

---