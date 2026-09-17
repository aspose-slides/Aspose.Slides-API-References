---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapeelement/
---
## ShapeElement クラス

同じアウトラインと塗りつぶしプロパティを持つシェイプの一部を表します。

ShapeElement 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/ja/aspose.slides/shapeelement/parent_shape/) | 要素が作成された Shape_PPT を返します。<br/>            読み取り専用 [`Shape`](/slides/python-net/ja/aspose.slides/shape). |
| [`path_points`](/slides/python-net/ja/aspose.slides/shapeelement/path_points/) | 要素のパスのジオメトリを定義する点の配列を取得します。 |
| [`path_types`](/slides/python-net/ja/aspose.slides/shapeelement/path_types/) | 要素のパス内の各ポイントのタイプを指定するバイト値の配列を取得します。<br/>            <br/>**0**  ポイントが図形の開始であることを示します。<br/><br/><br/>**1**  ポイントが直線の2つの端点のうちの1つであることを示します。<br/><br/><br/>**3**  ポイントが立方ベジエスプラインの終点または制御点であることを示します。<br/><br/><br/>**7**  低位3ビット以外のすべてのビットをマスクし、ポイントタイプを示します。<br/><br/><br/>**16**  対応するセグメントが破線であることを指定します。<br/><br/><br/>**32**  ポイントがマーカーであることを指定します。<br/><br/><br/>**128**  ポイントが閉じたサブパス（図形）の最後のポイントであることを指定します。<br/><br/><br/>**129**  線分の端点であり、かつ閉じたサブパスの最後のポイントであるデータポイントであることを示します。 |
| [`fill_source`](/slides/python-net/ja/aspose.slides/shapeelement/fill_source/) | 要素の塗りつぶし方法に関する情報を返します。<br/>            読み取り専用 [`ShapeElementFillSource`](/slides/python-net/ja/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/ja/aspose.slides/shapeelement/stroke_source/) | 要素の輪郭描画方法に関する情報を返します。<br/>            読み取り専用 [`ShapeElementStrokeSource`](/slides/python-net/ja/aspose.slides/shapeelementstrokesource). |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)