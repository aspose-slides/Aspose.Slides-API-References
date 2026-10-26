---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API リファレンス
description: "埋め込みWAVファイルを使用して新しいオーディオフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。埋め込まれたオーディオは Presentation::get_Audios コレクションに追加されます。"
type: docs
weight: 300
url: /ja/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) メソッド


埋め込みWAVファイルを使用して新しいオーディオフレームを作成し、指定したインデックスでシェイプコレクションに挿入します。埋め込みオーディオは[Presentation::get_Audios](../../presentation/get_audios/)コレクションに追加されます。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | オーディオフレームを挿入する0から始まるインデックスです。 |
| x | **float** | 新しいオーディオフレームのx座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームのy座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 埋め込むWAVオーディオデータを含む入力ストリームです。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)です。

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) メソッド


既存の[Presentation::get_Audios](../../presentation/get_audios/)リストのオーディオオブジェクトを使用して、新しいオーディオフレームを作成し、指定したインデックスでシェイプコレクションに挿入します。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | オーディオフレームを挿入する0から始まるインデックスです。 |
| x | **float** | 新しいオーディオフレームのx座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームのy座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 埋め込むための[Presentation::get_Audios](../../presentation/get_audios/)コレクションからの[IAudio](../../iaudio/)インスタンスです。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)です。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [Stream](../../../system.io/stream/)
* クラス [ShapeCollection](../)
* クラス [IAudio](../../iaudio/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)