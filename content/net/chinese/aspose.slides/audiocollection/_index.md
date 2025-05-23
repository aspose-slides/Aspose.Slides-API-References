---
title: AudioCollection
second_title: Aspose.Slides for .NET API 参考
description: 表示嵌入音频文件的集合
type: docs
weight: 760
url: /zh/aspose.slides/audiocollection/
---
## AudioCollection class

表示嵌入音频文件的集合。

```csharp
public class AudioCollection : DomObject<Presentation>, IAudioCollection
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.slides/audiocollection/count) { get; } | 返回集合中的音频文件数量。 只读Int32。 |
| [IsSynchronized](../../aspose.slides/audiocollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否同步（线程安全）。 只读Boolean。 |
| [Item](../../aspose.slides/audiocollection/item) { get; } | 获取指定索引处的元素。 只读[`IAudio`](../iaudio)。 |
| [SyncRoot](../../aspose.slides/audiocollection/syncroot) { get; } | 返回同步根。 只读Object。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_1)(byte[]) | 从字节数组创建音频并将其添加到演示文稿。 |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio)(IAudio) | 添加来自另一个演示文稿的音频文件的副本。 |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_2)(Stream) | 从流中创建音频并将其添加到演示文稿。 |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_3)(Stream, LoadingStreamBehavior) | 从流中创建音频并将其添加到演示文稿。 |
| [CopyTo](../../aspose.slides/audiocollection/copyto)(Array, int) | 从指定索引开始将音频复制到指定数组。 |
| [GetEnumerator](../../aspose.slides/audiocollection/getenumerator)() | 返回一个遍历集合的枚举器。 |

### 也可以看看

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [IAudioCollection](../iaudiocollection)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
