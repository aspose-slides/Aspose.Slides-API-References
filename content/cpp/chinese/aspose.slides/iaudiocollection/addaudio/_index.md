---
title: AddAudio()
second_title: Aspose.Slides for C++ API 参考
description: 从另一个演示文稿中添加音频文件的副本。
type: docs
weight: 14
url: /zh/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method

添加来自另一个演示文稿的音频文件的副本。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 源音频。 |

### 返回值

已添加音频。

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method

从流中创建并添加音频到演示文稿。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要添加音频的流。 |

### 返回值

已添加音频。

已弃用
:   使用 AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior)。此方法将在 17.10 版本中移除。

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

从流中创建并添加音频到演示文稿。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要添加视频音频的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于流的行为。 |

### 返回值

已添加音频。

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method

从字节数组创建并添加音频到演示文稿。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 字节。 |

### 返回值

已添加音频。

## 另见

* 枚举 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IAudio](../../iaudio/)
* 类 [IAudioCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)