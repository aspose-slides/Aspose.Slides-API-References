---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API リファレンス
description: 埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。
type: docs
weight: 261
url: /ja/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) メソッド


埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、指定したインデックスでシェイプコレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 埋め込む WAV オーディオデータを含む入力ストリーム。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)です。

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) メソッド


既存の Presentation.Audios リストから取得したオーディオオブジェクトを使用して、新しいオーディオフレームを作成し、指定したインデックスでシェイプコレクションに挿入します。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios コレクションから取得した埋め込み対象の [IAudio](../../iaudio/) インスタンス。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IShapeCollection](../)
* クラス [IAudio](../../iaudio/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)