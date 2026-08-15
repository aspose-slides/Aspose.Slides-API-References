---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立一個內嵌 WAV 檔案的新音訊框架，並將其插入至指定索引的形狀集合中。內嵌的音訊會加入到 Presentation::get_Audios 集合中。"
type: docs
weight: 300
url: /zh-hant/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

建立一個內嵌 WAV 檔案的新音訊框架，並將其插入至指定索引的形狀集合中。內嵌的音訊會加入到 [Presentation::get_Audios](../../presentation/get_audios/) 集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標（單位為點）。 |
| y | **float** | 新音訊框架的 y 座標（單位為點）。 |
| width | **float** | 新音訊框架的寬度（單位為點）。 |
| height | **float** | 新音訊框架的高度（單位為點）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要內嵌的 WAV 音訊資料的輸入串流。 |

### 返回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) 方法

建立一個新音訊框架，並使用來自 [Presentation::get_Audios](../../presentation/get_audios/) 清單的現有音訊物件，將其插入至指定索引的形狀集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標（單位為點）。 |
| y | **float** | 新音訊框架的 y 座標（單位為點）。 |
| width | **float** | 新音訊框架的寬度（單位為點）。 |
| height | **float** | 新音訊框架的高度（單位為點）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 來自 [Presentation::get_Audios](../../presentation/get_audios/) 集合的 [IAudio](../../iaudio/) 實例，用於內嵌。 |

### 返回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)