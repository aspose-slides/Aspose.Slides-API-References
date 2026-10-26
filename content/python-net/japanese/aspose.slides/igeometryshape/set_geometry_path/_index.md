---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅に対して相対的でなければなりません。シェイプのタイプを ([`IGeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_type)) から [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します.


```python
def set_geometry_path(self, geometry_path):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) | ジオメトリパス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | 空のパスが見つかりました |



### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`IGeometryShape`](/slides/python-net/ja/aspose.slides/igeometryshape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)