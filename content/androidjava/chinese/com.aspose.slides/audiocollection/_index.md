---
title: AudioCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示嵌入式音频文件的集合。
type: docs
url: /zh/com.aspose.slides/audiocollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**全部已实现的接口：**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

表示嵌入式音频文件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中音频文件的数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 添加来自另一个演示文稿的音频文件副本。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 从流创建并添加音频到演示文稿。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 从流创建并添加音频到演示文稿。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 从字节数组创建并添加音频到演示文稿。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将音频复制到指定数组，从指定索引开始。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```

返回集合中音频文件的数量。只读 int。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

获取指定索引处的元素。只读 [IAudio](../../com.aspose.slides/iaudio)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

添加来自另一个演示文稿的音频文件副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 源音频。 |

**返回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

从流创建并添加音频到演示文稿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要添加音频的流。 |

**返回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

从流创建并添加音频到演示文稿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要添加视频音频的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

从字节数组创建并添加音频到演示文稿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audioData | byte[] | 音频字节。 |

**返回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将音频复制到指定数组，从指定索引开始。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 数组。 |
| index | int | 索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

返回遍历集合的枚举器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 一个可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 用于整个集合的 java.util.Iterator。