---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
埋め込みWAVファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

### 戻り値

The newly created [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio_stream | **io.RawIOBase** | 埋め込む WAV オーディオ データを含む入力ストリーム。 |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

The newly created [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | Presentation.Audios コレクションからの [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) インスタンス。 |



### 関連項目
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* クラス [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)