---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立一個嵌入 WAV 檔案的新音訊框，並將其加入至圖形集合的末端。嵌入的音訊會加入到 Presentation::get_Audios 集合中。"
type: docs
weight: 287
url: /zh-hant/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

建立一個嵌入 WAV 檔案的新音訊框，並將它加入至圖形集合的末端。嵌入的音訊會加入到 [Presentation::get_Audios](../../presentation/get_audios/) 集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新音訊框的 x 座標，以點為單位。 |
| y | **float** | 新音訊框的 y 座標，以點為單位。 |
| width | **float** | 新音訊框的寬度，以點為單位。 |
| height | **float** | 新音訊框的高度，以點為單位。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入之 WAV 音訊資料的輸入串流。 |

### 回傳值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 備註

以下範例說明如何建立 [Audio](../../audio/) 框架。
```cpp
// 實例化一個代表簡報檔的 Presentation 類別
auto pres = System::MakeObject<Presentation>();

// 取得第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 將 wav 音訊檔載入為串流
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// 加入音訊框
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// 設定音訊的播放模式與音量
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// 將 PowerPoint 檔案寫入磁碟
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) 方法

建立一個新的音訊框，並使用 [Presentation::get_Audios](../../presentation/get_audios/) 清單中現有的音訊物件，將其加入至圖形集合的末端。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新音訊框的 x 座標，以點為單位。 |
| y | **float** | 新音訊框的 y 座標，以點為單位。 |
| width | **float** | 新音訊框的寬度，以點為單位。 |
| height | **float** | 新音訊框的高度，以點為單位。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 來自 [Presentation::get_Audios](../../presentation/get_audios/) 集合的 [IAudio](../../iaudio/) 實例。 |

### 回傳值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)