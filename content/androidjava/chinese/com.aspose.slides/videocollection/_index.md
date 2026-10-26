---
title: VideoCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示 Video 对象的集合。
type: docs
url: /zh/com.aspose.slides/videocollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**全部实现的接口：**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

表示 Video 对象的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中视频文件的数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 从另一个演示文稿中添加视频文件的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 从流中创建并添加视频到演示文稿。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 从字节数组创建并添加视频到演示文稿。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将视频复制到指定数组，从指定索引开始。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```


返回集合中视频文件的数量。只读 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


获取指定索引处的元素。只读 [IVideo](../../com.aspose.slides/ivideo)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


从另一个演示文稿中添加视频文件的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 源视频。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的视频。
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


从流中创建并添加视频到演示文稿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要从中添加视频文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的 [IVideo](../../com.aspose.slides/ivideo)。
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


从字节数组创建并添加视频到演示文稿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| videoData | byte[] | 视频字节。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的视频。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将视频复制到指定数组，从指定索引开始。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 数组。 |
| index | int | 索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**返回：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 一个可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 一个用于整个集合的 java.util.Iterator。