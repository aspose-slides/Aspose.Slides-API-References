---
title: AddAudio()
second_title: Aspose.Slides C++ API 参考
description: 从另一个演示文稿中添加音频文件的副本。
type: docs
weight: 53
url: /zh/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) 方法

添加音频文件的副本，来源于另一个演示文稿。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 源音频。 |

### 返回值

已添加的音频。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) 方法

从流创建并添加音频到演示文稿。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用于添加音频的流。 |

### 返回值

已添加的音频。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法

从流创建并添加音频到演示文稿。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用于添加视频音频的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于流的行为。 |

### 返回值

已添加的音频。

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) 方法

从字节数组创建并添加音频到演示文稿。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 字节。 |

### 返回值

已添加的音频。

## 另请参阅

* 枚举 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IAudio](../../iaudio/)
* 类 [AudioCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)