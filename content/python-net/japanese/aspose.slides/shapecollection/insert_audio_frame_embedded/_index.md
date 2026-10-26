---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
埋め込みWAVファイルを使用して新しいオーディオフレームを作成し、指定したインデックスでシェイプ コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | オーディオフレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio_stream | **io.RawIOBase** | 埋め込む WAV オーディオ データを含む入力ストリームです。 |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
新しいオーディオフレームを作成し、Presentation.Audios リストの既存のオーディオ オブジェクトを使用して、指定したインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | オーディオフレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）です。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）です。 |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | 埋め込むための Presentation.Audios コレクションからの [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) インスタンスです。 |



### 関連項目
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* クラス [`IAudioFrame`](/slides/python-net/ja/aspose.slides/iaudioframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)