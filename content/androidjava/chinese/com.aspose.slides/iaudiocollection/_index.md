---
title: IAudioCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示嵌入式音频文件的集合。
type: docs
url: /zh/com.aspose.slides/iaudiocollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

表示嵌入式音频文件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 从另一个演示文稿中添加音频文件的副本。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 从流创建并向演示文稿添加音频。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 从流创建并向演示文稿添加音频。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 从字节数组创建并向演示文稿添加音频。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


获取指定索引处的元素。只读 [IAudio](../../com.aspose.slides/iaudio)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


从另一个演示文稿中添加音频文件的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 源音频。 |

**返回：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


从流创建并向演示文稿添加音频。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要添加音频的流。 |

**返回：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


从流创建并向演示文稿添加音频。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要添加视频音频的流。 |
| loadingStreamBehavior | int | 将应用于流的 [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior)。 |

**返回：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


从字节数组创建并向演示文稿添加音频。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audioData | byte[] | 音频字节。 |

**返回：**
[IAudio](../../com.aspose.slides/iaudio) - 已添加的音频。