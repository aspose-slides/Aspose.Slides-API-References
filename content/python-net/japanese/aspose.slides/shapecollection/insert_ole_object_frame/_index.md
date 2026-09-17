---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
新しいOLEオブジェクトフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。

### 戻り値

新しく作成された[`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe)。

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | OLEオブジェクトフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいOLEフレームのx座標（ポイント単位）。 |
| y | **float** | 新しいOLEフレームのy座標（ポイント単位）。 |
| width | **float** | 新しいOLEフレームの幅（ポイント単位）。 |
| height | **float** | 新しいOLEフレームの高さ（ポイント単位）。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo) | 埋め込みOLEデータ情報（[`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)）。 |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
新しいOLEオブジェクトフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。

### 戻り値

新しく作成されたOLEオブジェクトフレーム。

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | OLEオブジェクトフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいOLEフレームのx座標（ポイント単位）。 |
| y | **float** | 新しいOLEフレームのy座標（ポイント単位）。 |
| width | **float** | 新しいOLEフレームの幅（ポイント単位）。 |
| height | **float** | 新しいOLEフレームの高さ（ポイント単位）。 |
| class_name | **str** | OLEオブジェクトのクラス名。 |
| path | **str** | リンクされたファイルへのパス。 <br/><br/>このパスはプレゼンテーションに文字通り保存されます。<br/><br/>相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

### 参照
* クラス [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)
* クラス [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)