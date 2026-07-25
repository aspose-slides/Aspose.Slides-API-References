---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API リファレンス
description: 埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。埋め込まれたオーディオは Presentation.Audios コレクションに追加されます。
type: docs
weight: 248
url: /ja/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) メソッド

埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。埋め込まれたオーディオは Presentation.Audios コレクションに追加されます。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 埋め込む WAV オーディオデータを含む入力ストリームです。 |

### 戻り値

新しく作成された [IAudioFrame](../../iaudioframe/) です。

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) メソッド

既存の Presentation.Audios リストからのオーディオオブジェクトを使用して、新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios コレクションからの [IAudio](../../iaudio/) インスタンスです。 |

### 戻り値

新しく作成された [IAudioFrame](../../iaudioframe/) です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IShapeCollection](../)
* クラス [IAudio](../../iaudio/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)