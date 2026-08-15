---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個嵌入 WAV 檔案的新音訊框架，並將其插入至指定索引的形狀集合中。嵌入的音訊會新增至 Presentation.Audios 集合中。
type: docs
weight: 261
url: /zh-hant/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

建立一個嵌入 WAV 檔案的新音訊框架，並將其插入至指定索引的形狀集合中。嵌入的音訊會新增至 Presentation.Audios 集合中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標，單位為點。 |
| y | **float** | 新音訊框架的 y 座標，單位為點。 |
| width | **float** | 新音訊框架的寬度，單位為點。 |
| height | **float** | 新音訊框架的高度，單位為點。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入之 WAV 音訊資料的輸入串流。 |

### Return Value

新建立的 [IAudioFrame](../../iaudioframe/)。

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) 方法

建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其插入至指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標，單位為點。 |
| y | **float** | 新音訊框架的 y 座標，單位為點。 |
| width | **float** | 新音訊框架的寬度，單位為點。 |
| height | **float** | 新音訊框架的高度，單位為點。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 要嵌入的來自 Presentation.Audios 集合的 [IAudio](../../iaudio/) 實例。 |

### Return Value

新建立的 [IAudioFrame](../../iaudioframe/)。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [IShapeCollection](../)
* 類別 [IAudio](../../iaudio/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)