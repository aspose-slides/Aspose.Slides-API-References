---
title: AddVideo()
second_title: Aspose.Slides for C++ API 參考
description: 從另一個簡報中新增影片檔案的副本。
type: docs
weight: 53
url: /zh-hant/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) 方法


新增一個影片檔案的副本，來源於另一個簡報。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 來源影片。 |

### 返回值

已新增的影片。

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法


從串流建立並加入影片至簡報。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用於加入影片檔案的串流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 將套用於串流的行為。 |

### 返回值

已新增[IVideo](../../ivideo/)。

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) 方法


從位元組陣列建立並加入影片至簡報。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) 位元組。 |

### 返回值

已新增的影片。

## 另請參閱

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [VideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)