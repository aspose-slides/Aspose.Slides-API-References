---
title: AddVideo()
second_title: Aspose.Slides C++ API 参考
description: 从另一个演示文稿中添加视频文件的副本。
type: docs
weight: 14
url: /zh/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) method

Adds a copy of an video file from an another presentation.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 源视频。 |

### 返回值

已添加视频。

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Creates and adds a video to a presentation from stream.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要从中添加视频文件的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于流的行为。 |

### 返回值

已添加[IVideo](../../ivideo/)。

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) method

Creates and adds a video to a presentation from byte array.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) 字节。 |

### 返回值

已添加视频。

## 另请参见

* 枚举 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IVideo](../../ivideo/)
* 类 [IVideoCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)