---
title: AddAudio()
second_title: Aspose.Slides for C++ API 參考文件
description: 從另一個簡報中新增音訊檔案的副本。
type: docs
weight: 14
url: /zh-hant/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) 方法

從另一個簡報中新增音訊檔案的副本。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 來源音訊。 |

### 傳回值

已新增音訊。

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) 方法

從串流建立並新增音訊至簡報。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用於新增音訊的串流。 |

### 傳回值

已新增音訊。

已棄用
:   Use AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). The method will be removed in version 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法

從串流建立並新增音訊至簡報。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用於新增影片音訊的串流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 將套用於串流的行為。 |

### 傳回值

已新增音訊。

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) 方法

從位元組陣列建立並新增音訊至簡報。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 位元組。 |

### 傳回值

已新增音訊。

## 另請參閱

* 列舉 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IAudio](../../iaudio/)
* 類別 [IAudioCollection](../)
* 類別 [Stream](../../../system.io/stream/)
* 名稱空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)