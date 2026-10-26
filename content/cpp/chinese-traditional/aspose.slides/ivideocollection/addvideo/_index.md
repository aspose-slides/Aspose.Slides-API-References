---
title: AddVideo()
second_title: Aspose.Slides for C++ API 參考
description: 從另一個簡報中新增影片檔案的副本。
type: docs
weight: 14
url: /zh-hant/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) method

從另一個簡報中新增影片檔案的副本。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 來源影片。 |

### Return Value

已新增影片。

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

從串流建立並新增影片至簡報。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要從中新增影片檔案的串流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 將套用於串流的行為。 |

### Return Value

已新增 [IVideo](../../ivideo/)。

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) method

從位元組陣列建立並新增影片至簡報。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) 位元組。 |

### Return Value

已新增影片。

## See Also

* 列舉 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IVideo](../../ivideo/)
* 類別 [IVideoCollection](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)