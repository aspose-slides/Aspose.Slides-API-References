---
title: AddVideo()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のプレゼンテーションからビデオファイルのコピーを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) メソッド


別のプレゼンテーションからビデオファイルのコピーを追加します。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ソースビデオ。 |

### 戻り値

追加されたビデオ。

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド


ストリームからプレゼンテーションにビデオを作成して追加します。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ビデオファイルを追加するストリーム。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | ストリームに適用される動作。 |

### 戻り値

Added [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) メソッド


バイト配列からプレゼンテーションにビデオを作成して追加します。

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) バイト。 |

### 戻り値

追加されたビデオ。

## 参照

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)