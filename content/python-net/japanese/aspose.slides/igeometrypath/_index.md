---
title: IGeometryPath class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometrypath/
---
## IGeometryPath クラス

GeometryShape のジオメトリ パスを表します

IGeometryPath 型は以下のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/ja/aspose.slides/igeometrypath/path_data/) | GeometryShape のジオメトリ パスをパス セグメントの配列として返します。 |
| [`fill_mode`](/slides/python-net/ja/aspose.slides/igeometrypath/fill_mode/) | 塗りつぶしモードを設定します |
| [`stroke`](/slides/python-net/ja/aspose.slides/igeometrypath/stroke/) | ストロークの外観を設定します |

## メソッド

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ja/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | パスの末尾に線を追加します |
| [`line_to(self, x, y)`](/slides/python-net/ja/aspose.slides/igeometrypath/line_to/#float-float) | パスの末尾に線を追加します |
| [`line_to(self, point, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | パスの指定された位置に線を追加します |
| [`line_to(self, x, y, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/line_to/#float-float-int) | パスの指定された位置に線を追加します |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ja/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | パスの末尾に 3 次ベジェ曲線を追加します |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ja/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | パスの末尾に 3 次ベジェ曲線を追加します |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | パスの指定された位置に 3 次ベジェ曲線を追加します |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | パスの指定された位置に 3 次ベジェ曲線を追加します |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ja/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | パスの末尾に 2 次ベジェ曲線を追加します |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ja/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | パスの末尾に 2 次ベジェ曲線を追加します |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | パスの指定された位置に 2 次ベジェ曲線を追加します |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | パスの指定された位置に 2 次ベジェ曲線を追加します |
| [`move_to(self, point)`](/slides/python-net/ja/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | 次のポイント位置を設定します |
| [`move_to(self, x, y)`](/slides/python-net/ja/aspose.slides/igeometrypath/move_to/#float-float) | 次のポイント位置を設定します |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/igeometrypath/remove_at/#int) | ジオメトリ パスの指定されたインデックスのセグメントを削除します |
| [`close_figure(self)`](/slides/python-net/ja/aspose.slides/igeometrypath/close_figure/#) | このパスの現在の図形を閉じます |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ja/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | 指定された円弧をパスに追加します |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)