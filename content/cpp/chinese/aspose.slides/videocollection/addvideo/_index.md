---
title: AddVideo()
second_title: Aspose.Slides for C++ API 参考
description: 从另一个演示文稿中添加视频文件的副本。
type: docs
weight: 53
url: /zh/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) 方法

添加一个来自另一演示文稿的视频文件的副本。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 源视频。 |

### 返回值

已添加的视频。

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法

从流创建并添加视频到演示文稿。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用于添加视频文件的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于流的行为。 |

### 返回值

已添加 [IVideo](../../ivideo/)。

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) 方法

从字节数组创建并添加视频到演示文稿。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) 字节。 |

### 返回值

已添加的视频。

## 另请参见

* 枚举 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IVideo](../../ivideo/)
* 类 [VideoCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)