---
title: AddAudio()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のプレゼンテーションからオーディオ ファイルのコピーを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) メソッド

別のプレゼンテーションからオーディオ ファイルのコピーを追加します。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | ソース オーディオ。 |

### 戻り値

追加されたオーディオ。

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) メソッド

ストリームからプレゼンテーションにオーディオを作成し、追加します。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | オーディオを追加するストリーム。 |

### 戻り値

追加されたオーディオ。

非推奨
:   AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior) を使用してください。このメソッドはバージョン 17.10 で削除されます。

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド

ストリームからプレゼンテーションにビデオのオーディオを作成し、追加します。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ビデオオーディオを追加するストリーム。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | ストリームに適用される動作。 |

### 戻り値

追加されたオーディオ。

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) メソッド

バイト配列からプレゼンテーションにオーディオを作成し、追加します。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) バイト。 |

### 戻り値

追加されたオーディオ。

## 参照

* 列挙型 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IAudio](../../iaudio/)
* クラス [IAudioCollection](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)