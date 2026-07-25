---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API リファレンス
description: "埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。埋め込みオーディオは Presentation::get_Audios コレクションに追加されます。"
type: docs
weight: 287
url: /ja/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) メソッド

埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。埋め込みオーディオは [Presentation::get_Audios](../../presentation/get_audios/) コレクションに追加されます。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 埋め込む WAV オーディオ データを含む入力ストリーム。 |

### 戻り値

新しく作成された [IAudioFrame](../../iaudioframe/)。

## 備考

以下の例は [Audio](../../audio/) フレームの作成方法を示します。

```cpp
// プレゼンテーションファイルを表すプレゼンテーションクラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>();

// 最初のスライドを取得します
auto slide = pres->get_Slides()->idx_get(0);
// wav 音声ファイルをストリームにロードします
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// オーディオフレームを追加します
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// オーディオの再生モードと音量を設定します
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// PowerPoint ファイルをディスクに書き込みます
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) メソッド

既存の [Presentation::get_Audios](../../presentation/get_audios/) リストからのオーディオ オブジェクトを使用して、新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [IAudio](../../iaudio/) のインスタンス（[Presentation::get_Audios](../../presentation/get_audios/) コレクションから）。 |

### 戻り値

新しく作成された [IAudioFrame](../../iaudioframe/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)