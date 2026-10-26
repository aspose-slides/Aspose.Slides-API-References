---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
埋め込みWAVファイルを持つ新しいオーディオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | オーディオフレームを挿入する対象のゼロベースインデックスです。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio_stream | **io.RawIOBase** | 埋め込む WAV オーディオデータを含む入力ストリームです。 |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
既存の Presentation.Audios リストから取得したオーディオオブジェクトを使用し、新しいオーディオフレームを作成して、指定されたインデックスで shape コレクションに挿入します。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | オーディオフレームを挿入する対象のゼロベースインデックスです。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | Presentation.Audios コレクションから埋め込むための [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) インスタンスです。 |



### 参照
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* クラス [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)