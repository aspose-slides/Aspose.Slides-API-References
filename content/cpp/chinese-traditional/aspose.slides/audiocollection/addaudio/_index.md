---
title: AddAudio()
second_title: Aspose.Slides for C++ API 參考
description: 從另一個簡報新增音訊檔案的副本。
type: docs
weight: 53
url: /zh-hant/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) 方法


從另一個簡報新增音訊檔案的副本。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 來源音訊。 |

### 返回值

已新增的音訊。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) 方法


從串流建立並新增音訊至簡報。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要新增音訊的串流。 |

### 返回值

已新增的音訊。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法


從串流建立並新增音訊至簡報。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要新增視訊音訊的串流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 將套用於串流的行為。 |

### 返回值

已新增的音訊。

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) 方法


從位元組陣列建立並新增音訊至簡報。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 位元組。 |

### 返回值

已新增的音訊。

## 另請參閱

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)