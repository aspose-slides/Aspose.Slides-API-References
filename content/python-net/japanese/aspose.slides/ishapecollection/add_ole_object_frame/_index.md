---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

### Returns

新しく作成された [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo) | 埋め込まれた OLE データ情報（[`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)）。 |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

### Returns

新しく作成された [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| class_name | **str** | OLE オブジェクトのクラス名。 |
| path | **str** | リンクされたファイルへのパス。<br/><br/>このパスはプレゼンテーションにそのまま保存されます。<br/><br/>相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くときにファイルにアクセスできなくなります。 |



### 参照
* クラス [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)
* クラス [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)