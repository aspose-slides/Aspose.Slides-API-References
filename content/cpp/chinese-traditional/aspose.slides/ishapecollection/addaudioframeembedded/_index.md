---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個內嵌 WAV 檔案的新音訊框架，並將其加入形狀集合的末端。內嵌的音訊會加入 Presentation.Audios 集合。
type: docs
weight: 248
url: /zh-hant/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

建立一個內嵌 WAV 檔案的新音訊框架，並將其加入形狀集合的末端。內嵌的音訊會加入 Presentation.Audios 集合。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新音訊框架的 x 座標，以點為單位。 |
| y | **float** | 新音訊框架的 y 座標，以點為單位。 |
| width | **float** | 新音訊框架的寬度，以點為單位。 |
| height | **float** | 新音訊框架的高度，以點為單位。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入之 WAV 音訊資料的輸入串流。 |

### 傳回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) 方法

建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其加入形狀集合的末端。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新音訊框架的 x 座標，以點為單位。 |
| y | **float** | 新音訊框架的 y 座標，以點為單位。 |
| width | **float** | 新音訊框架的寬度，以點為單位。 |
| height | **float** | 新音訊框架的高度，以點為單位。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 來自 Presentation.Audios 集合的 [IAudio](../../iaudio/) 實例。 |

### 傳回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [IShapeCollection](../)
* 類別 [IAudio](../../iaudio/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)