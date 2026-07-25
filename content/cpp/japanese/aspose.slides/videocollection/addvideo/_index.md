---
title: AddVideo()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のプレゼンテーションからビデオ ファイルのコピーを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) メソッド

別のプレゼンテーションからビデオ ファイルのコピーを追加します。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ソースビデオ。 |

### 戻り値

追加されたビデオ。

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド

ストリームからプレゼンテーションにビデオを作成して追加します。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ビデオ ファイルを追加するためのストリーム。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | ストリームに適用される動作。 |

### 戻り値

追加された [IVideo](../../ivideo/)。

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) メソッド

バイト配列からプレゼンテーションにビデオを作成して追加します。

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) バイト。 |

### 戻り値

追加されたビデオ。

## 参照

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [VideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)