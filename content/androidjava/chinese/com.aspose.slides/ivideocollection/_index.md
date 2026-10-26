---
title: IVideoCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Video 对象的集合。
type: docs
url: /zh/com.aspose.slides/ivideocollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

表示 Video 对象的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 从另一个演示文稿添加视频文件的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 从流创建并将视频添加到演示文稿。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 从字节数组创建并将视频添加到演示文稿。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

获取指定索引处的元素。只读 [IVideo](../../com.aspose.slides/ivideo)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

从另一个演示文稿添加视频文件的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 源视频。 |

**返回值:**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的视频。

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

从流创建并将视频添加到演示文稿。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要从中添加视频文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回值:**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的 [IVideo](../../com.aspose.slides/ivideo)。

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

从字节数组创建并将视频添加到演示文稿。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| videoData | byte[] | 视频字节。 |

**返回值:**
[IVideo](../../com.aspose.slides/ivideo) - 已添加的视频。