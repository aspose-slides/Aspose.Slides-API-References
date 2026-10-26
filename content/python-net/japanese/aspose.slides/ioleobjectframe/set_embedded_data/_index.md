---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
OLE 埋め込みデータに関する情報を設定します。

```python
def set_embedded_data(self, embedded_data):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo) | 埋め込みデータ [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo) |

### 備考

このメソッドは新しいデータを反映するようにオブジェクトのプロパティを変更し、IsObjectLink フラグを false に設定して、OLE オブジェクトが埋め込まれていることを示します。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | embeddedData パラメーターが None の場合。 |

### 参照
* クラス [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)
* クラス [`IOleObjectFrame`](/slides/python-net/ja/aspose.slides/ioleobjectframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)