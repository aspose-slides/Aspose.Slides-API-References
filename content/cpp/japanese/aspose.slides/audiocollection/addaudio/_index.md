---
title: AddAudio()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のプレゼンテーションからオーディオ ファイルのコピーを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) メソッド

別のプレゼンテーションからオーディオ ファイルのコピーを追加します。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | ソースオーディオ。 |

### 戻り値

追加されたオーディオ。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) メソッド

ストリームからプレゼンテーションにオーディオを作成して追加します。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | オーディオを追加するストリーム。 |

### 戻り値

追加されたオーディオ。

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド

ストリームからプレゼンテーションにオーディオを作成して追加します。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 動画オーディオを追加するストリーム。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | ストリームに適用される動作。 |

### 戻り値

追加されたオーディオ。

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) メソッド

バイト配列からプレゼンテーションにオーディオを作成して追加します。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) バイト。 |

### 戻り値

追加されたオーディオ。

## 参照

* 列挙体 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IAudio](../../iaudio/)
* クラス [AudioCollection](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)