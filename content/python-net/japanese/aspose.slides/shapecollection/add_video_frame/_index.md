---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IVideoFrame`](/slides/python-net/ja/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいビデオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | **str** | 埋め込むビデオファイルのパスまたは名前。 |

## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IVideoFrame`](/slides/python-net/ja/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, video):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しいビデオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| video | [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo) | ビデオフレームに埋め込む [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo)。 |

### 参照
* クラス [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo)
* クラス [`IVideoFrame`](/slides/python-net/ja/aspose.slides/ivideoframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)