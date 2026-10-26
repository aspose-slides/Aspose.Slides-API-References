---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
新しい OLE オブジェクト フレームを作成し、指定したインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | OLE オブジェクト フレームを挿入する、0 から始まるインデックス。 |
| x | **float** | 新しい OLE フレームの X 座標（ポイント）。 |
| y | **float** | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント）。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)）。 |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
新しい OLE オブジェクト フレームを作成し、指定したインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | OLE オブジェクト フレームを挿入する、0 から始まるインデックス。 |
| x | **float** | 新しい OLE フレームの X 座標（ポイント）。 |
| y | **float** | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント）。 |
| class_name | **str** | OLE オブジェクトのクラス名。 |
| path | **str** | リンクされたファイルへのパス。 <br/><br/>このパスはプレゼンテーションにそのまま保存されます。<br/><br/>相対パスが指定された場合、別のディレクトリからプレゼンテーションを開く際にファイルにアクセスできなくなります。 |



### 参照
* class [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)