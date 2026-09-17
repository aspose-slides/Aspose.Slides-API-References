---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。埋め込まれたオーディオは Presentation.Audios コレクションに追加されます。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio_stream | **io.RawIOBase** | 埋め込む WAV オーディオデータを含む入力ストリーム。 |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
既存の Presentation.Audios リスト内のオーディオオブジェクトを使用して、新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | Presentation.Audios コレクションからの [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) インスタンス。 |

### 参照
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* クラス [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)